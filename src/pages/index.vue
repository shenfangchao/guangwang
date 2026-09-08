<script setup lang="ts">
const documents = [
  { path: '/terms', index: '01', title: 'Terms of Service', description: 'Rules for using SeylO, including live rooms, Paid Events, Coins, and account responsibilities.' },
  { path: '/privacy', index: '02', title: 'Privacy Policy', description: 'What information SeylO processes, why it is needed, and the choices available to you.' },
  { path: '/community-guidelines', index: '03', title: 'Community Guidelines', description: 'Standards that keep live conversations, profiles, events, and messages respectful and safe.' },
  { path: '/account-deletion', index: '04', title: 'Account Deletion', description: 'How to permanently delete your SeylO account and what happens to your data and Coins.' },
]
</script>

<template>
  <main class="site-home">
    <section class="home-hero">
      <p class="eyebrow">VOICE-FIRST SOCIAL COMMUNITY</p>
      <div class="brand-lockup" aria-label="SeylO">
        <span class="brand-mark" aria-hidden="true"><i /><i /><i /><i /><i /></span>
        <h1>SeylO</h1>
      </div>
      <p class="home-lead">
        Listen first. Join the conversation when you are ready. Stay connected with the people you choose.
      </p>
    </section>

    <section class="document-grid" aria-label="Legal and safety documents">
      <RouterLink v-for="document in documents" :key="document.path" :to="document.path" class="document-card">
        <span class="document-index">{{ document.index }}</span>
        <h2>{{ document.title }}</h2>
        <p>{{ document.description }}</p>
        <span class="document-link">READ DOCUMENT <span aria-hidden="true">↗</span></span>
      </RouterLink>
    </section>

    <footer class="site-footer">
      <span>© 2026 SeylO</span>
      <a href="mailto:maryj@moesbrands.cyou">maryj@moesbrands.cyou</a>
    </footer>
  </main>
</template>
