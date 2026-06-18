<template>
  <div class="csp-wrapper">
    <div class="csp-container">
      <header class="csp-header">
        <h1>Smirra Policy Agreement</h1>
        <p class="csp-updated">Last updated: June 25, 2025</p>
      </header>

      <p class="csp-intro">
        Smirra adheres to a zero-tolerance policy for any form of child
        abuse, exploitation, and/or sexual behavior. We are committed to
        protecting the safety of underage users and ensuring that the
        platform is not used for inappropriate behavior. Any users who
        violate the Smirra Policy will have their accounts
        deleted and may face legal consequences.
      </p>

      <!-- 1. Age Restriction -->
      <section class="csp-section">
        <h2>1. Age Restriction</h2>
        <ul>
          <li>Users must be at least 18 years old to use Smirra.</li>
          <li>
            Falsifying one's age to access the platform is strictly
            prohibited and will result in the suspension or deletion of the
            account.
          </li>
        </ul>
      </section>

      <!-- 2. Prohibited Activities -->
      <section class="csp-section">
        <h2>2. Prohibited Activities</h2>
        <p>
          Smirra uses both automated and manual systems to detect underage
          activity and Child Sexual Abuse and Exploitation (CSAE). Any
          attempt to circumvent these systems is strictly prohibited.
          Prohibited activities include, but are not limited to, the
          following:
        </p>

        <h3>Sexualization of Minors and Child Sexual Abuse and Exploitation (CSAE)</h3>
        <ul>
          <li>
            Sharing, creating, or distributing content involving child
            sexual abuse or exploitation.
          </li>
          <li>
            Any content related to minor sexual attraction, such as
            discussions, sexual performances, or wearing sexually suggestive
            clothing.
          </li>
          <li>
            Any form of child nudity or sexually suggestive descriptions,
            including artistic representations such as drawings or
            animations.
          </li>
        </ul>

        <h3>Harmful or Dangerous Behavior Involving Minors</h3>
        <ul>
          <li>
            Threatening, encouraging, or engaging in physical violence
            against minors.
          </li>
          <li>Psychological abuse, coercion, or manipulation of minors.</li>
          <li>
            Depicting or encouraging minors to engage in dangerous
            activities.
          </li>
          <li>Promoting or depicting neglect or trafficking of minors.</li>
        </ul>
      </section>

      <!-- 3. Minor Representation on the Platform -->
      <section class="csp-section">
        <h2>3. Minor Representation on the Platform</h2>
        <ul>
          <li>
            Minors are strictly prohibited from appearing in live streams,
            videos, or any other form of content.
          </li>
          <li>Creating or managing accounts for minors is prohibited.</li>
          <li>Falsifying age to gain access to the platform is prohibited.</li>
        </ul>
      </section>

      <!-- 4. Reporting Mechanism -->
      <section class="csp-section">
        <h2>4. Reporting Mechanism</h2>
        <p>
          Any incidents of child abuse will be reported to the National
          Center for Missing and Exploited Children (NCMEC) or other
          relevant authorities, as required by applicable laws. Users can
          report potential violations via the in-app reporting function or
          by emailing
          
        </p>
      </section>

      <!-- 5. Prohibited Users -->
      <section class="csp-section">
        <h2>5. Prohibited Users</h2>
        <p>
          Users who have been convicted of child-related crimes (including
          but not limited to sexual assault, physical abuse, neglect, or
          trafficking) are strictly prohibited from using Smirra.
        </p>
      </section>

      <!-- 6. Enforcement and Transparency -->
      <section class="csp-section">
        <h2>6. Enforcement and Transparency</h2>
        <p>
          Smirra will strictly enforce the Child Safety Policy, and any
          violations will result in immediate penalties. Depending on the
          severity of the violation, Smirra may cooperate with law
          enforcement agencies to conduct investigations.
        </p>
      </section>

      <!-- 7. User Education -->
      <section class="csp-section">
        <h2>7. User Education</h2>
        <p>Smirra educates users about child safety through the following methods:</p>
        <ul>
          <li>Providing the platform's child safety policy.</li>
          <li>
            Offering reminders and alerts during content creation and
            sharing to avoid potential dangers.
          </li>
        </ul>
      </section>

      <!-- 8. Additional Resources -->
      <section class="csp-section">
        <h2>8. Additional Resources</h2>
        <p>
          If you encounter child exploitation or abuse outside of Smirra, we
          recommend contacting the following resources based on your
          location:
        </p>
        <ul>
          <li>
            <strong>North America, Australia, New Zealand:</strong> National
            Center for Missing and Exploited Children (NCMEC)
          </li>
          <li>
            <strong>Europe:</strong> Law enforcement reporting channels for
            child sexual coercion and extortion
          </li>
          <li>
            <strong>South America and Other Regions:</strong> International
            Centre for Missing &amp; Exploited Children
          </li>
        </ul>
      </section>

      <!-- 9. Commitment to Child Safety -->
      <section class="csp-section">
        <h2>9. Commitment to Child Safety</h2>
        <p>
          Smirra is committed to continuously evaluating and improving its
          policies, systems, and practices to ensure the highest standards
          of child safety on the platform. Our goal is to provide a safe and
          inclusive space for everyone.
        </p>
      </section>
    </div>

    <!-- 固定悬浮联系信息条 -->
    <div class="csp-floating-bar">
      <span class="csp-floating-label">Contact:</span>
      <a class="csp-floating-email" 
        >Smirra098772@gmail.com</a
      >
    </div>
  </div>
</template>

<script>
export default {
  name: 'HiLiveChildSafetyPolicy'
}
</script>

<style scoped>
.csp-wrapper {
  position: relative;
  min-height: 100vh;
}

.csp-container {
  max-width: 860px;
  margin: 0 auto;
  padding: 2.5rem 1.5rem 6rem; /* 底部留白，避免被悬浮条遮挡 */
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    'Helvetica Neue', Arial, sans-serif;
  color: #2b2d33;
  line-height: 1.7;
  font-size: 16px;
}

.csp-header {
  border-bottom: 2px solid #e2e4ea;
  padding-bottom: 1rem;
  margin-bottom: 1.5rem;
}

.csp-header h1 {
  font-size: 1.9rem;
  font-weight: 700;
  margin: 0 0 0.4rem;
  color: #1a1c20;
}

.csp-updated {
  font-size: 0.9rem;
  color: #6b6f76;
  margin: 0;
}

.csp-intro {
  background: #f6f7fa;
  border-left: 4px solid #d64545;
  padding: 1rem 1.25rem;
  border-radius: 6px;
  margin-bottom: 2rem;
  font-size: 0.97rem;
}

.csp-section {
  margin-bottom: 2.25rem;
}

.csp-section h2 {
  font-size: 1.3rem;
  font-weight: 700;
  color: #1a1c20;
  border-bottom: 1px solid #e2e4ea;
  padding-bottom: 0.5rem;
  margin-bottom: 1rem;
}

.csp-section h3 {
  font-size: 1.05rem;
  font-weight: 600;
  color: #33363d;
  margin: 1.25rem 0 0.5rem;
}

.csp-section p {
  margin: 0 0 0.9rem;
  text-align: justify;
}

.csp-section ul,
.csp-section ol {
  margin: 0 0 1rem;
  padding-left: 1.5rem;
}

.csp-section li {
  margin-bottom: 0.6rem;
}

.csp-section a {
  color: #d64545;
  text-decoration: none;
  word-break: break-word;
}

.csp-section a:hover {
  text-decoration: underline;
}

/* 固定在页面底部的半透明悬浮条 */
.csp-floating-bar {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 1000;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
  padding: 0.85rem 1rem;
  background: rgba(0, 0, 0, 0.6);
  backdrop-filter: blur(4px);
  -webkit-backdrop-filter: blur(4px);
  color: #fff;
  font-size: 0.95rem;
}

.csp-floating-label {
  font-weight: 600;
  opacity: 0.85;
}

.csp-floating-email {
  color: #fff;
  text-decoration: underline;
  word-break: break-word;
}

.csp-floating-email:hover {
  opacity: 0.85;
}

@media (max-width: 600px) {
  .csp-container {
    padding: 1.5rem 1rem 6.5rem;
    font-size: 15px;
  }

  .csp-floating-bar {
    flex-direction: column;
    gap: 0.15rem;
    padding: 0.7rem 1rem;
    font-size: 0.88rem;
  }
}
</style>
