<script setup lang="ts">
defineOptions({
  name: 'PrivacyPage',
})

const appName = 'Mavioo'
const developerName = 'Mavioo'
const contactEmail = 'Mavioo8162158984@icloud.com'
const effectiveDate = 'June 15, 2026'
</script>

<template>
  <article class="privacy-page">
    <header class="privacy-header">
      <h1>{{ appName }} Privacy Policy</h1>
      <p>
        Effective date: {{ effectiveDate }}
      </p>
      <p>
        This Privacy Policy applies to the {{ appName }} mobile application
        published on Google Play and operated by {{ developerName }}. It
        explains how {{ appName }} accesses, collects, uses, shares, stores, and
        protects user data.
      </p>
      <p>
        Privacy contact: <a :href="`mailto:${contactEmail}`">{{ contactEmail }}</a>
      </p>
    </header>

    <section>
      <h2>1. Information We Collect</h2>
      <p>
        We collect only the information needed to provide, maintain, secure, and
        improve {{ appName }}. Depending on how you use the app, the information
        may include the categories below.
      </p>
      <h3>1.1 Account and profile information</h3>
      <p>
        When you create or manage an account, we may collect information such as
        your nickname, email address, password or authentication credentials,
        age or date of birth, gender, country or region, profile photo, profile
        video, and other profile details you choose to provide.
      </p>
      <h3>1.2 User content and communications</h3>
      <p>
        If you use social, messaging, voice, video, or content-sharing features,
        we may process the content you provide, such as text messages, comments,
        photos, videos, audio, profile materials, and related metadata. Other
        users may see content that you choose to share publicly or with them.
      </p>
      <h3>1.3 Device, usage, and diagnostics information</h3>
      <p>
        We may collect technical information such as device model, operating
        system version, app version, language settings, IP address, network
        status, advertising identifier or app set identifier where permitted,
        usage events, feature interactions, crash logs, performance data, and
        diagnostic information.
      </p>
      <h3>1.4 Permissions and sensitive data</h3>
      <p>
        {{ appName }} asks for device permissions only when they are needed for
        app features. Camera access may be used for profile photos, video
        content, and video calls. Microphone access may be used for voice
        messages and video calls. Photo or media access may be used when you
        choose to upload or save images and videos. Notification permission may
        be used to send service messages, account alerts, and feature
        notifications. If a feature requires location, we will request location
        permission and explain the purpose before collecting location data.
      </p>
      <h3>1.5 Payment and transaction information</h3>
      <p>
        If you purchase paid features, subscriptions, or digital content,
        payment processing is handled by Google Play or another authorized
        payment provider. We may receive and store purchase status, product
        identifiers, order identifiers, transaction history, and other records
        needed to provide the paid service, resolve disputes, prevent fraud, and
        comply with legal obligations. We do not collect or store full payment
        card numbers.
      </p>
      <h3>1.6 Third-party login information</h3>
      <p>
        If you sign in using a third-party account such as Google or Facebook,
        we may receive information authorized by you and provided by that
        service, such as account ID, display name, profile photo, email address,
        access token, or ID token. The information available to us depends on
        your settings with the third-party service.
      </p>
    </section>

    <section>
      <h2>2. How We Use Information</h2>
      <p>
        {{ appName }} uses user data for the following purposes:
      </p>
      <ul>
        <li>To create, verify, secure, and manage user accounts.</li>
        <li>To provide app features such as profiles, messaging, media sharing, and calls.</li>
        <li>To process purchases, subscriptions, refunds, and account balances.</li>
        <li>To send service notices, security alerts, and support messages.</li>
        <li>To detect, prevent, and respond to fraud, abuse, security incidents, and policy violations.</li>
        <li>To analyze app performance, fix crashes, improve stability, and develop new features.</li>
        <li>To comply with applicable laws, valid legal requests, and platform requirements.</li>
      </ul>
      <p>
        We do not sell personal and sensitive user data.
      </p>
    </section>

    <section>
      <h2>3. Third-Party Services and Sharing</h2>
      <p>
        We may share user data only as needed for the purposes described in this
        Privacy Policy. The types of recipients may include:
      </p>
      <ul>
        <li>Cloud hosting, storage, and content delivery providers.</li>
        <li>Analytics, attribution, crash reporting, and performance monitoring providers.</li>
        <li>Payment providers, including Google Play billing services.</li>
        <li>Customer support, moderation, anti-fraud, and security service providers.</li>
        <li>Law enforcement, regulators, courts, or other parties when required by law.</li>
        <li>Successors or affiliates if we are involved in a merger, acquisition, financing, reorganization, or sale of assets.</li>
      </ul>
      <p>
        Third-party services may include Google services such as Google Play,
        Firebase, Firebase Crashlytics, and Google Analytics for Firebase, and
        may also include attribution or social login providers such as AppsFlyer
        or Facebook if those features are integrated in the app. These providers
        process data under their own terms and privacy policies.
      </p>
    </section>

    <section>
      <h2>4. Data Security</h2>
      <p>
        We use reasonable administrative, technical, and organizational measures
        to protect user data. These measures may include HTTPS transmission,
        access controls, limited employee or contractor access, security review,
        and monitoring for misuse. No method of transmission or storage is
        completely secure, but we work to protect your information against
        unauthorized access, disclosure, alteration, and destruction.
      </p>
    </section>

    <section>
      <h2>5. Data Retention and Deletion</h2>
      <p>
        We retain personal information only for as long as needed to provide
        {{ appName }}, maintain security, resolve disputes, enforce our terms,
        comply with legal obligations, and support legitimate business needs.
        Retention periods may vary based on the type of data and the purpose for
        which it is processed.
      </p>
      <p>
        You may request access, correction, or deletion of your account and
        personal data by using in-app account tools where available or by
        contacting us at <a :href="`mailto:${contactEmail}`">{{ contactEmail }}</a>.
        After we verify your request, we will delete or anonymize data unless we
        need to keep certain information for legal, security, fraud prevention,
        dispute resolution, or transaction record purposes.
      </p>
      <p>
        Content that you shared with other users may remain visible if it has
        been copied, saved, or re-shared by others, or if retention is required
        for safety, legal, or platform compliance reasons.
      </p>
    </section>

    <section>
      <h2>6. Your Choices and Controls</h2>
      <p>
        You can choose not to provide certain information, but some features may
        not work without it. You can manage app permissions through your device
        settings. You can also update account information in the app where the
        feature is available, unsubscribe from optional communications, and
        contact us for privacy requests.
      </p>
    </section>

    <section>
      <h2>7. Children</h2>
      <p>
        {{ appName }} is not directed to children under 18. We do not knowingly
        collect personal information from children under 18. If we learn that a
        child under 18 has provided personal information, we will take
        reasonable steps to delete that information.
      </p>
    </section>

    <section>
      <h2>8. International Processing</h2>
      <p>
        {{ appName }} may process and store information on servers located in
        different countries or regions. Where required, we take steps designed
        to protect personal information in accordance with applicable data
        protection requirements.
      </p>
    </section>

    <section>
      <h2>9. Changes to This Privacy Policy</h2>
      <p>
        We may update this Privacy Policy from time to time. If we make material
        changes, we will notify users by posting the updated policy in the app,
        on this page, or through another appropriate method. The effective date
        at the top of this page shows when this Privacy Policy was last updated.
      </p>
    </section>

    <section>
      <h2>10. Contact Us</h2>
      <p>
        If you have questions, requests, or complaints about this Privacy Policy
        or the privacy practices of {{ appName }}, please contact
        {{ developerName }} at
        <a :href="`mailto:${contactEmail}`">{{ contactEmail }}</a>.
      </p>
    </section>
  </article>
</template>

<style scoped>
.privacy-page {
  min-height: 100vh;
  padding: 24px 16px 40px;
  background-color: #000;
  color: #fff;
  font-size: 15px;
  line-height: 1.7;
}

.privacy-header,
section {
  max-width: 960px;
  margin: 0 auto 22px;
}

h1,
h2,
h3,
p {
  margin: 0;
}

h1 {
  margin-bottom: 12px;
  color: #d91d24;
  font-size: 26px;
  line-height: 1.25;
  text-align: center;
}

h2 {
  margin-bottom: 10px;
  color: #d91d24;
  font-size: 20px;
  line-height: 1.35;
}

h3 {
  margin: 12px 0 6px;
  color: #ff6f74;
  font-size: 16px;
  line-height: 1.4;
}

p + p {
  margin-top: 10px;
}

ul {
  margin: 8px 0 0 18px;
  padding: 0;
}

li + li {
  margin-top: 6px;
}

a {
  color: #ffb3b6;
  text-decoration: underline;
  overflow-wrap: anywhere;
}
</style>
