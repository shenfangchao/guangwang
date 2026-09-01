<script setup lang="ts">
const email = 'SeylO@gmail.com'
</script>

<template>
  <main class="legal-page">
    <header class="legal-hero deletion-hero">
      <RouterLink to="/" class="legal-brand">SEYLO</RouterLink>
      <p class="legal-kicker">ACCOUNT · 04</p>
      <h1>Account Deletion</h1>
      <p class="legal-updated">Permanent and irreversible</p>
    </header>

    <nav class="legal-nav" aria-label="Legal documents">
      <RouterLink to="/terms">Terms</RouterLink>
      <RouterLink to="/privacy">Privacy</RouterLink>
      <RouterLink to="/community-guidelines">Guidelines</RouterLink>
      <RouterLink to="/account-deletion">Delete account</RouterLink>
    </nav>

    <p class="legal-intro warning-intro">
      You can initiate deletion directly inside SeylO. Deleting the app from your device does not delete your account.
    </p>

    <section class="legal-section deletion-steps">
      <h2>Delete your account in the app</h2>
      <ol>
        <li><span>1</span><p>Open <strong>SeylO</strong> and sign in to the account you want to delete.</p></li>
        <li><span>2</span><p>Open your <strong>Profile</strong>, then select <strong>Settings</strong>.</p></li>
        <li><span>3</span><p>Tap <strong>Delete account</strong>.</p></li>
        <li><span>4</span><p>Review the consequences and confirm permanent deletion.</p></li>
      </ol>
      <p>
        We may ask you to reauthenticate or confirm a verification code so another person cannot delete your account without permission.
      </p>
    </section>

    <section class="legal-section">
      <h2>What deletion removes</h2>
      <ul>
        <li>Your account access, profile, username, photo, biography, and interests.</li>
        <li>Your follow relationships, block list, room and Event associations.</li>
        <li>Your active message history and associated account data.</li>
        <li>Your unused Coin balance and Paid Event tickets.</li>
      </ul>
      <p>
        Deletion is irreversible after processing. Unused Coins and tickets are permanently forfeited, have no cash value, and cannot be transferred, withdrawn, refunded, or restored because the account was deleted.
      </p>
    </section>

    <section class="legal-section">
      <h2>Limited retention</h2>
      <p>
        Active account information is deleted or de-identified after processing. Limited records may remain temporarily in backups or be retained when reasonably necessary for security, fraud prevention, transaction integrity, moderation, dispute resolution, enforcement, or legal obligations. We do not use retained information for unrelated purposes. SeylO does not record or store live room audio or one-to-one video-call audio or video.
      </p>
    </section>

    <section class="legal-section">
      <h2>Need help?</h2>
      <p>
        If you cannot access the in-app deletion control, contact <a :href="`mailto:${email}?subject=SeylO%20Account%20Deletion`">{{ email }}</a> from the email address associated with your account, or include your username and sign-in phone number. We will verify account ownership before assisting. Email support is an alternative for access problems; it is not required when the in-app deletion flow is available.
      </p>
      <a class="legal-cta" :href="`mailto:${email}?subject=SeylO%20Account%20Deletion`">CONTACT SUPPORT</a>
    </section>
  </main>
</template>

<style scoped>
@import '../styles/legal.css';
</style>
