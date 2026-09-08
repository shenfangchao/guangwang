<script setup lang="ts">
const email = 'lilye@taneshiasprinting.pics'
</script>

<template>
  <main class="legal-page">
    <header class="legal-hero">
      <RouterLink to="/" class="legal-brand">SEYLO</RouterLink>
      <p class="legal-kicker">SAFETY · 03</p>
      <h1>Community Guidelines</h1>
      <p class="legal-updated">Effective: September 1, 2026</p>
    </header>

    <nav class="legal-nav" aria-label="Legal documents">
      <RouterLink to="/terms">Terms</RouterLink>
      <RouterLink to="/privacy">Privacy</RouterLink>
      <RouterLink to="/community-guidelines">Guidelines</RouterLink>
      <RouterLink to="/account-deletion">Delete account</RouterLink>
    </nav>

    <p class="legal-intro">
      SeylO works best when people can listen, speak, and connect without being harassed or misled. These rules apply to profiles, live rooms, Events, messages, video calls, and every other part of SeylO.
    </p>

    <section class="legal-section">
      <h2>1. Be authentic</h2>
      <p>
        Do not impersonate another person or organization, misrepresent your identity or affiliation, create deceptive accounts, or use another person's photo or private information without permission. Parody or fan accounts must be clearly identified and must not mislead others.
      </p>
    </section>

    <section class="legal-section">
      <h2>2. Respect people and the microphone</h2>
      <p>
        Let others speak, respect the host's room rules, and leave when asked. Hosts may manage the speaking queue, mute speakers, remove participants, or end a room. Disagreement is allowed; targeted harassment, bullying, intimidation, stalking, threats, hateful conduct, sexual harassment, and coordinated abuse are not.
      </p>
    </section>

    <section class="legal-section">
      <h2>3. Protect safety and privacy</h2>
      <p>
        Do not promote violence, self-harm, dangerous challenges, exploitation, trafficking, or illegal activity. Never share child sexual abuse material, grooming content, non-consensual intimate material, or sexual content involving minors. Do not reveal another person's phone number, address, precise location, private messages, or other sensitive information without permission.
      </p>
      <p>
        If someone is in immediate danger, contact local emergency services. SeylO's reporting tools are not an emergency service.
      </p>
    </section>

    <section class="legal-section">
      <h2>4. Keep Events honest</h2>
      <p>
        Event titles, descriptions, schedules, hosts, speakers, and Paid Event ticket prices must be accurate. Do not bait-and-switch, hide the Coin price, promise guaranteed results, sell access to prohibited content, or use Paid Events as scams. Coins and Event tickets cannot be exchanged for cash, transferred, used for gambling, or used to move money between users.
      </p>
    </section>

    <section class="legal-section">
      <h2>5. No spam or manipulation</h2>
      <p>
        Do not send repetitive or unwanted messages, create fake engagement, artificially inflate attendance or follows, run phishing or investment scams, misuse invitations, post malware, scrape user data, evade blocks, or coordinate false reports. Commercial promotion is allowed only where SeylO expressly permits it and must be truthful.
      </p>
    </section>

    <section class="legal-section">
      <h2>6. Respect rights</h2>
      <p>
        Share only content you have the right to use. Do not infringe copyright, trademark, privacy, publicity, or other rights. Live rooms are not recorded by SeylO, but you should still assume other participants can hear and remember anything said on an open microphone.
      </p>
    </section>

    <section class="legal-section">
      <h2>7. Report and block</h2>
      <p>
        Use the report control on a profile, room, Event, or message when content or conduct violates these Guidelines. Include an accurate reason and relevant context. You can also block a user; blocking removes mutual access and limits profiles, rooms, messages, and calls within SeylO. Reports are confidential and the reported user is not told who submitted them.
      </p>
      <p>
        We prioritize reports based on severity and available information and aim to respond promptly. Do not submit knowingly false, retaliatory, or abusive reports. For urgent safety concerns or help with a report, email <a :href="`mailto:${email}?subject=SeylO%20Safety%20Report`">{{ email }}</a>.
      </p>
    </section>

    <section class="legal-section">
      <h2>8. Enforcement</h2>
      <p>
        Depending on context, severity, and history, we may remove or limit content, mute or remove a speaker, close a room, cancel an Event, refund eligible tickets in Coins, restrict communication or hosting, issue a warning, suspend or terminate an account, preserve evidence, or contact authorities. Severe violations may result in immediate removal. Attempts to evade enforcement may lead to additional action.
      </p>
    </section>
  </main>
</template>

<style scoped>
@import '../styles/legal.css';
</style>
