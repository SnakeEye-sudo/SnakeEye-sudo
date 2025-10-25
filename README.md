<!-- ULTIMATE DARK PROFILE README FOR SnakeEye-sudo -->

<!-- HEADER: Neon tech banner with animated snake and glowing username -->
<p align="center">
  <svg width="100%" height="220" viewBox="0 0 1200 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="SnakeEye-sudo Tech Banner">
    <defs>
      <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#0b0e14"/>
        <stop offset="50%" stop-color="#0f1420"/>
        <stop offset="100%" stop-color="#0b0e14"/>
      </linearGradient>
      <linearGradient id="neon" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#00E5FF"/>
        <stop offset="100%" stop-color="#7C4DFF"/>
      </linearGradient>
      <filter id="glow"><feGaussianBlur stdDeviation="3" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
      <path id="snakePath" d="M20,150 C200,80 400,200 600,120 C800,40 1000,180 1180,100" fill="none"/>
    </defs>
    <rect width="1200" height="220" rx="14" fill="url(#bg)"/>
    <g filter="url(#glow)">
      <text x="50%" y="95" text-anchor="middle" fill="url(#neon)" font-family="'JetBrains Mono', 'Fira Code', monospace" font-size="44" letter-spacing="2">SnakeEye-sudo</text>
      <text x="50%" y="135" text-anchor="middle" fill="#9aa4b2" font-family="'Inter', system-ui, sans-serif" font-size="16">Tech • Automation • Cloud • Open-Source • DevOps</text>
    </g>
    <!-- Animated snake -->
    <g>
      <use href="#snakePath" stroke="#1d263b" stroke-width="2"/>
      <circle r="6" fill="#00E5FF">
        <animateMotion dur="10s" repeatCount="indefinite" keyPoints="0;1" keyTimes="0;1" calcMode="linear">
          <mpath href="#snakePath"/>
        </animateMotion>
      </circle>
      <circle r="4" fill="#7C4DFF" opacity="0.7">
        <animateMotion dur="10s" begin="-1s" repeatCount="indefinite"><mpath href="#snakePath"/></animateMotion>
      </circle>
      <circle r="3" fill="#00ffc6" opacity="0.5">
        <animateMotion dur="10s" begin="-2s" repeatCount="indefinite"><mpath href="#snakePath"/></animateMotion>
      </circle>
    </g>
  </svg>
</p>

<!-- BADGE ROW: robust marketplace alternatives (no broken images) -->
<p align="center">
  <!-- Stars/Followers/Views via shields.io (robust, no API keys) -->
  <img src="https://img.shields.io/github/followers/SnakeEye-sudo?label=Followers&logo=github&style=for-the-badge&color=0ea5e9&labelColor=0b0e14" alt="Followers"/>
  <img src="https://img.shields.io/github/stars/SnakeEye-sudo?label=Stars&logo=github&style=for-the-badge&color=8b5cf6&labelColor=0b0e14" alt="Stars"/>
  <img src="https://komarev.com/ghpvc/?username=SnakeEye-sudo&style=for-the-badge&color=00e5ff&label=PROFILE+VIEWS" alt="Profile views"/>
  <!-- Marketplace-like badges (static) to avoid breakage -->
  <img src="https://img.shields.io/badge/Theme-Ultimate%20Dark-111827?style=for-the-badge&logo=github&logoColor=white" alt="Theme: Ultimate Dark"/>
  <img src="https://img.shields.io/badge/Made%20with-Markdown-0f766e?style=for-the-badge&logo=markdown&logoColor=white" alt="Made with Markdown"/>
</p>

---

## 📆 Events README
- Auto-updated timeline of commits, releases, and activity appears below in Live Stats & Metrics and Wisdom sections. No external APIs are used; all data is derived from Git internals and repository metadata.

## 🧩 Readme Projects Display
- Highlighted pinned repositories with clean badges.

<p align="center">
  <a href="https://github.com/SnakeEye-sudo?tab=repositories"><img src="https://img.shields.io/badge/Explore%20my%20Projects-0b0e14?style=for-the-badge&logo=github&logoColor=00E5FF&labelColor=0b0e14&color=1f2937" alt="Explore my projects"/></a>
</p>

## 🔁 readme-files-updater-for-release
- This repo employs a GitHub Action to refresh sections (Wisdom/Stats/Stack) every 6 hours using only Git commands and local repository parsing.

---

## 🚀 ABOUT ME
- Tech tinkerer and automation-first developer.
- Love DevOps, CI/CD, Cloud Infra, SRE, and Developer Experience.
- Passion: building resilient pipelines, clean tooling, and elegant CLI/UX.

---

## 📊 LIVE STATS & METRICS
<p align="center">
  <img src="https://img.shields.io/badge/Commits-$(commits)-111827?style=for-the-badge&logo=git&logoColor=F05032" alt="Commits"/>
  <img src="https://img.shields.io/badge/Repos-$(repos)-111827?style=for-the-badge&logo=github" alt="Repos"/>
  <img src="https://img.shields.io/badge/Open%20Issues-$(issues)-111827?style=for-the-badge&logo=github" alt="Issues"/>
  <img src="https://img.shields.io/badge/Pull%20Requests-$(prs)-111827?style=for-the-badge&logo=github" alt="PRs"/>
</p>
<details>
<summary>How these update</summary>
These placeholders are replaced by a scheduled Action scraping only local repo/user-owned data (no external API).
</details>

---

## 🏆 GITHUB TROPHIES
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=SnakeEye-sudo&theme=algolia&no-frame=true&no-bg=true&row=1&column=7" alt="GitHub Trophies" />
</p>

---

## 🧠 Language & Tech Stack
- Auto-generated list from repos (includes languages, cloud, database, automation tools). This section updates via Action.

<details open>
<summary><b>Current Snapshot</b></summary>

<!-- START:TECH_STACK --><!-- filled by action -->
- Languages: Bash, Python, JavaScript, TypeScript, Go, Rust, C/C++
- Web: HTML, CSS, Node.js, React, Next.js, Express
- DevOps: Git, GitHub Actions, Docker, Docker Compose, Kubernetes, Helm, Terraform
- Cloud: AWS, GCP, Azure, Cloudflare
- Databases: PostgreSQL, MySQL, MongoDB, Redis, SQLite
- Messaging/Streaming: Kafka, RabbitMQ
- Observability: Prometheus, Grafana, OpenTelemetry
- Security: Trivy, Snyk, Dependabot
- CI/CD: Actions, ArgoCD, Jenkins
- Testing: Jest, PyTest, Playwright
- Automation: Make, Ansible
<!-- END:TECH_STACK -->

</details>

---

## 🤝 CONNECT WITH ME
- LinkedIn: https://www.linkedin.com/in/sangam-k-799ba8373/
- X (Twitter): https://x.com/SangamKrishna3
- Instagram: https://www.instagram.com/sangam_krishnaa_/
- Email: Krishna.sangam11@gmail.com

<p align="center">
<a href="https://www.linkedin.com/in/sangam-k-799ba8373/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://x.com/SangamKrishna3"><img src="https://img.shields.io/badge/X%20(Twitter)-111827?style=for-the-badge&logo=x&logoColor=white" alt="X"/></a>
<a href="https://www.instagram.com/sangam_krishnaa_/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>
<a href="mailto:Krishna.sangam11@gmail.com"><img src="https://img.shields.io/badge/Email-0b0e14?style=for-the-badge&logo=gmail&logoColor=EA4335&labelColor=0b0e14&color=111827" alt="Email"/></a>
</p>

---

## ☕ SUPPORT
<a href="https://buymeacoffee.com/snakeeye"><img src="https://img.shields.io/badge/Buy%20me%20a%20coffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=111827" alt="Buy me a coffee"/></a>

---

## 🧩 WISDOM FOR THE DAY
<p align="center">
  <svg width="100%" height="120" viewBox="0 0 1200 120" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Daily Wisdom">
    <defs>
      <linearGradient id="w" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#111827"/>
        <stop offset="100%" stop-color="#0b0e14"/>
      </linearGradient>
      <linearGradient id="wtext" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#00E5FF"/>
        <stop offset="100%" stop-color="#00FFC6"/>
      </linearGradient>
    </defs>
    <rect width="1200" height="120" rx="8" fill="url(#w)"/>
    <text id="wisdom-text" x="50%" y="65" text-anchor="middle" fill="url(#wtext)" font-family="'Inter', system-ui, sans-serif" font-size="20">{{WISDOM_OF_THE_DAY}}</text>
  </svg>
</p>

<p align="center">
  <sub>Auto-refreshes every 6 hours via GitHub Actions without external APIs.</sub>
</p>

---

<!-- FOOTER: Minimal neon wave + 3 mini SVG accents -->
<p align="center">
  <svg width="100%" height="80" viewBox="0 0 1200 80" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Footer Wave">
    <defs>
      <linearGradient id="wave" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#7C4DFF"/>
        <stop offset="50%" stop-color="#00E5FF"/>
        <stop offset="100%" stop-color="#00FFC6"/>
      </linearGradient>
    </defs>
    <path d="M0 40 Q 300 0 600 40 T 1200 40" stroke="url(#wave)" stroke-width="2" fill="none">
      <animate attributeName="d" dur="6s" repeatCount="indefinite" values="M0 40 Q 300 0 600 40 T 1200 40; M0 40 Q 300 70 600 40 T 1200 40; M0 40 Q 300 0 600 40 T 1200 40"/>
    </path>
    <g>
      <circle cx="40" cy="40" r="3" fill="#7C4DFF"/>
      <circle cx="70" cy="20" r="2" fill="#00E5FF"/>
      <circle cx="100" cy="55" r="2" fill="#00FFC6"/>
    </g>
  </svg>
  <br/>
  <sub>© SnakeEye-sudo • Built with love for dark mode</sub>
</p>

<!-- MARKERS the Action will replace -->
<!-- START:WISDOM -->Daily progress beats perfect plans.<!-- END:WISDOM -->
<!-- START:STATS commits=0 repos=0 issues=0 prs=0 -->
<!-- END:STATS -->
