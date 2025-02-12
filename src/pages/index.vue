<script setup>
import { ref } from "vue";
import CryptoJS from "crypto-js";

let ivvvi = ref("1234657890123456");
const inputText = ref(""); // 明文或密文
const secretKey = ref(""); // 密钥
const outputText = ref(""); // 结果
// AES 加密
const encrypt = () => {
  if (!inputText.value || !secretKey.value || !ivvvi.value) {
    alert("请输入文本和密钥和Iv");
    return;
  }
  const key = CryptoJS.enc.Utf8.parse(secretKey.value.padEnd(16, "0")); // 确保密钥长度为 16
  const iv = CryptoJS.enc.Utf8.parse(`${ivvvi.value}`); // 固定 IV，必须 16 字节
  const encrypted = CryptoJS.AES.encrypt(inputText.value, key, {
    iv: iv,
    mode: CryptoJS.mode.CBC,
    padding: CryptoJS.pad.Pkcs7
  }).toString();
  outputText.value = encrypted;
};
// AES 解密
const decrypt = () => {
  if (!inputText.value || !secretKey.value || !ivvvi.value) {
    alert("请输入加密文本和密钥和Iv");
    return;
  }
  try {
    const key = CryptoJS.enc.Utf8.parse(secretKey.value.padEnd(16, "0")); // 确保密钥长度为 16
    const iv = CryptoJS.enc.Utf8.parse(ivvvi.value); // 固定 IV，必须 16 字节
    const bytes = CryptoJS.AES.decrypt(inputText.value, key, {
      iv: iv,
      mode: CryptoJS.mode.CBC,
      padding: CryptoJS.pad.Pkcs7
    });
    outputText.value = bytes.toString(CryptoJS.enc.Utf8);
    if (!outputText.value) throw new Error("解密失败");
  } catch (error) {
    alert("解密失败，请检查密钥是否正确");
  }
};

const copy = async () => {
  if (!outputText.value) {
        alert("没有可复制的内容");
        return;
      }
      try {
        await navigator.clipboard.writeText(outputText.value);
         
        
      } catch (err) {
        alert("复制失败：" + err);
      }
}


// 清空输入
const clearFields = () => {
  inputText.value = "";
  secretKey.value = "";
  outputText.value = "";
  ivvvi.value= '';
};
</script>

<template>
  <div class="container">
    <h2>AES 加密/解密工具</h2>
    <input v-model="inputText" placeholder="请输入明文或密文" />
    <input v-model="secretKey"  placeholder="请输入密钥" />
    <input v-model="outputText" placeholder="加密/解密结果" readonly />
    <input v-model="ivvvi" placeholder="iv密钥（16）" :minlength=16 />

    <div class="buttons">
      <button @click="encrypt">加密</button>
      <button @click="decrypt">解密</button>
      <button @click="clearFields">清空</button>
      <button @click="copy">复制</button>
    </div>
  </div>
</template>

<style scoped>
.container {
  width: 400px;
  margin: 50px auto;
  padding: 20px 20px;
  text-align: center;
  border: 1px solid #ddd;
  border-radius: 8px;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}
input {
  display: block;
  width: 96%;
  margin: 10px 0;
  padding: 8px;
  border: 1px solid #ddd;
  border-radius: 4px;
  height: 50px;
 
}
.buttons {
  display: flex;
  justify-content: space-between;
}
button {
  padding: 8px 15px;
  margin: 5px;
  border: none;
  background-color: #007bff;
  color: white;
  cursor: pointer;
  border-radius: 4px;
}
button:hover {
  background-color: #0056b3;
}
</style>