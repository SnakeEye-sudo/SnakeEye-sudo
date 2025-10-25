<!-- ULTIMATE DARK PROFILE README FOR SnakeEye-sudo -->

<!-- HEADER: Username-focused with animated SVG banner -->
<p align="center">
  <svg width="100%" height="180" viewBox="0 0 1200 180" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="SnakeEye-sudo Header">
    <defs>
      <linearGradient id="g1" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#0f0f13"/>
        <stop offset="50%" stop-color="#141925"/>
        <stop offset="100%" stop-color="#0f0f13"/>
      </linearGradient>
      <linearGradient id="neon" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#00E5FF"/>
        <stop offset="100%" stop-color="#7C4DFF"/>
      </linearGradient>
      <filter id="glow"><feGaussianBlur stdDeviation="3" result="coloredBlur"/><feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    </defs>
    <rect width="1200" height="180" fill="url(#g1)"/>
    <text x="50%" y="55%" text-anchor="middle" fill="url(#neon)" font-size="48" font-family="'Segoe UI', Roboto, Ubuntu, 'Helvetica Neue', Arial, sans-serif" filter="url(#glow)">SnakeEye-sudo</text>
    <text x="50%" y="78%" text-anchor="middle" fill="#9aa4b2" font-size="16" font-family="Consolas, 'Fira Code', Menlo, monospace">Automation • Cloud • DevOps • Data • Open Source</text>
  </svg>
</p>

---

<!-- SVG ANIMATIONS: 1) Snake, 2) Orbit, 3) Neon Waves, 4) Type Cursor -->

<!-- 1) Snake animation across contribution-like grid (SVG only, local) -->
<p align="center">
  <svg viewBox="0 0 600 120" width="100%" height="120" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="snakeGrad" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#00E676"/>
        <stop offset="100%" stop-color="#00BFA5"/>
      </linearGradient>
    </defs>
    <rect width="600" height="120" fill="#0b0f14" rx="8"/>
    <g fill="#101623">
      <!-- grid -->
      <g id="g">
        <rect x="20" y="20" width="10" height="10" rx="2"/>
      </g>
      <use href="#g" x="20"/><use href="#g" x="40"/><use href="#g" x="60"/><use href="#g" x="80"/>
      <use href="#g" x="100"/><use href="#g" x="120"/><use href="#g" x="140"/><use href="#g" x="160"/>
      <use href="#g" x="180"/><use href="#g" x="200"/><use href="#g" x="220"/><use href="#g" x="240"/>
      <use href="#g" x="260"/><use href="#g" x="280"/><use href="#g" x="300"/><use href="#g" x="320"/>
      <use href="#g" x="340"/><use href="#g" x="360"/><use href="#g" x="380"/><use href="#g" x="400"/>
      <use href="#g" x="420"/><use href="#g" x="440"/><use href="#g" x="460"/><use href="#g" x="480"/>
      <use href="#g" x="500"/><use href="#g" x="520"/><use href="#g" x="540"/><use href="#g" x="560"/>
    </g>
    <!-- snake path -->
    <path id="path" d="M 10 100 C 80 80, 120 40, 200 60 S 330 110, 420 70 520 55, 590 90" fill="none" stroke="url(#snakeGrad)" stroke-width="4" stroke-linecap="round"/>
    <circle r="6" fill="#00E676">
      <animateMotion dur="10s" repeatCount="indefinite" keyPoints="0;1" keyTimes="0;1">
        <mpath href="#path"/>
      </animateMotion>
    </circle>
  </svg>
</p>

<!-- 2) Orbit animation -->
<p align="center">
  <svg width="280" height="120" viewBox="0 0 280 120" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <radialGradient id="orb" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stop-color="#1f2940"/>
        <stop offset="100%" stop-color="#0b0f14"/>
      </radialGradient>
    </defs>
    <rect width="280" height="120" fill="#0b0f14" rx="10"/>
    <circle cx="140" cy="60" r="14" fill="#00E5FF"/>
    <g fill="#7C4DFF">
      <circle r="5">
        <animateMotion dur="6s" repeatCount="indefinite" path="M 140 60 m -50 0 a 50 50 0 1 0 100 0 a 50 50 0 1 0 -100 0"/>
      </circle>
      <circle r="3" fill="#00E676">
        <animateMotion dur="3s" repeatCount="indefinite" path="M 140 60 m -30 0 a 30 30 0 1 0 60 0 a 30 30 0 1 0 -60 0"/>
      </circle>
    </g>
  </svg>
</p>

<!-- 3) Neon waves -->
<p align="center">
  <svg width="100%" height="80" viewBox="0 0 1200 80" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="wave" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#00E5FF"/>
        <stop offset="100%" stop-color="#7C4DFF"/>
      </linearGradient>
    </defs>
    <rect width="1200" height="80" fill="#0b0f14"/>
    <path d="M0 40 Q 100 10 200 40 T 400 40 T 600 40 T 800 40 T 1000 40 T 1200 40" fill="none" stroke="url(#wave)" stroke-width="3">
      <animate attributeName="d" dur="8s" repeatCount="indefinite" values="M0 40 Q 100 10 200 40 T 400 40 T 600 40 T 800 40 T 1000 40 T 1200 40; M0 40 Q 100 70 200 40 T 400 40 T 600 40 T 800 40 T 1000 40 T 1200 40; M0 40 Q 100 10 200 40 T 400 40 T 600 40 T 800 40 T 1000 40 T 1200 40"/>
    </path>
  </svg>
</p>

<!-- 4) Type-cursor headline -->
<p align="center">
  <img alt="typing" src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=00E5FF&center=true&vCenter=true&width=1000&lines=Namaste%2C+I'm+Sangam+Krishna+(SnakeEye-sudo)!;Automation+%7C+Cloud+%7C+DevOps+%7C+Data+%7C+Open+Source;Building+cool+things+%F0%9F%9A%80"/>
</p>

---

## Events README
- Auto-updated log of profile README refresh runs (every 6 hours via GitHub Actions).
- See commit history for this file to track updates.

> Latest Events will be appended below by the workflow.

---

## Readme Projects Display
- Pinned and top repositories by stars/tags shown below.
- Uses native GitHub badges/links and local SVGs only.

<p>
  <a href="https://github.com/SnakeEye-sudo?tab=repositories&q=&type=&language=&sort=stargazers" target="_blank">
    <img src="https://custom-icon-badges.demolab.com/badge/Top%20Starred%20Repos-visit-0BDA51?style=for-the-badge&logo=star" alt="Top Starred"/>
  </a>
  <a href="https://github.com/SnakeEye-sudo?tab=repositories" target="_blank">
    <img src="https://custom-icon-badges.demolab.com/badge/Pinned%20Projects-check-2962FF?style=for-the-badge&logo=pin" alt="Pinned Projects"/>
  </a>
</p>

---

## readme-files-updater-for-release
- Recent releases and file updates across public repos (generated by local gh CLI in Action, no external API).
- The workflow parses git log and release tags and writes to this section.

> See the auto-updated block in this README after the first workflow run.

---

## 🚀 ABOUT ME
- Name: Sangam Krishna (SnakeEye-sudo)
- Location: India
- Tagline: Automating everything I touch — Cloud, CI/CD, Data, and delightful DX.
- Focus: DevOps, Infrastructure as Code, Cloud-Native, GitHub Automation, Data workflows.

---

## LIVE STATS & METRICS
- Contribution Streaks, Commit Activity, Language usage and Graphs built from repo data only.

<p>
  <!-- GitHub Stats Cards (shields-like images hosted on GitHub/cdn) -->
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=SnakeEye-sudo&show_icons=true&theme=tokyonight&hide_border=true" alt="stats"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SnakeEye-sudo&layout=compact&theme=tokyonight&hide_border=true" alt="langs"/>
</p>

<p>
  <img src="https://streak-stats.demolab.com?user=SnakeEye-sudo&theme=tokyonight&hide_border=true" alt="streak"/>
</p>

> Note: Visuals above are generated from public GitHub data badges. No paid/external API calls by our workflows.

---

## GITHUB TROPHIES
<p>
  <img src="https://github-profile-trophy.vercel.app/?username=SnakeEye-sudo&theme=algolia&no-frame=true&no-bg=true&margin-w=5" alt="trophies"/>
</p>

---

## Language & Tech Stack
Auto-derived from this account's public repositories and commit metadata by the Action.

- Languages: Python, JavaScript/TypeScript, Go, Shell, HTML/CSS, Markdown
- Databases: PostgreSQL, MySQL, SQLite, MongoDB
- Cloud: AWS, GCP, Azure, Cloudflare
- DevOps: Docker, Kubernetes, Terraform, Ansible, GitHub Actions
- Data/Automation: Pandas, Airflow, Bash, Make, CI/CD

> This list auto-updates based on repo changes and file detection.

---

## CONNECT WITH ME
- LinkedIn: https://www.linkedin.com/in/sangam-k-799ba8373/
- X (Twitter): https://x.com/SangamKrishna3
- Instagram: https://www.instagram.com/sangam_krishnaa_/
- Email: mailto:Krishna.sangam11@gmail.com

---

## SUPPORT
<p>
  <a href="https://buymeacoffee.com/snakeeye" target="_blank">
    <img src="https://img.shields.io/badge/Buy%20Me%20A%20Coffee-%23FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="BuyMeACoffee"/>
  </a>
</p>

---

## WISDOM FOR THE DAY
> Auto-updated every 6 hours by GitHub Action.

<details>
<summary>Today's rotating quote</summary>

<!-- The action writes the latest quote below between markers -->
<!-- QUOTE-START -->
Keep shipping. Momentum beats perfection.
<!-- QUOTE-END -->

</details>

---

<!-- FOOTER with username emphasis and 3 creative SVGs -->
<p align="center">
  <strong>— SnakeEye-sudo —</strong>
</p>
<p align="center">
  <!-- Footer snake line -->
  <svg width="100%" height="40" viewBox="0 0 1200 40" xmlns="http://www.w3.org/2000/svg">
    <path d="M0 20 Q 60 0 120 20 T 240 20 T 360 20 T 480 20 T 600 20 T 720 20 T 840 20 T 960 20 T 1080 20 T 1200 20" fill="none" stroke="#00E676" stroke-width="2">
      <animate attributeName="stroke-dasharray" values="0,200;200,0;0,200" dur="6s" repeatCount="indefinite"/>
    </path>
  </svg>
</p>
<p align="center">
  <!-- 3 small SVG accents: pulse dot, rotating triangle, pulsing ring -->
  <svg width="200" height="50" viewBox="0 0 200 50" xmlns="http://www.w3.org/2000/svg">
    <circle cx="20" cy="25" r="4" fill="#00E5FF">
      <animate attributeName="r" values="3;6;3" dur="2s" repeatCount="indefinite"/>
    </circle>
    <g transform="translate(90,25)">
      <polygon points="0,-8 7,6 -7,6" fill="#7C4DFF">
        <animateTransform attributeName="transform" type="rotate" from="0 0 0" to="360 0 0" dur="5s" repeatCount="indefinite"/>
      </polygon>
    </g>
    <circle cx="180" cy="25" r="8" fill="none" stroke="#00E676">
      <animate attributeName="stroke-width" values="1;3;1" dur="2.5s" repeatCount="indefinite"/>
    </circle>
  </svg>
</p>

<!-- WORKFLOW INSTRUCTIONS (kept here for reference) -->
<!--
Add .github/workflows/readme-refresh.yml with schedule: every 6 hours.
The workflow uses only GitHub Actions + bash + git to:
- Collect repo data (stars, topics, languages) via git ls-files and linguist heuristics
- Compute top languages and recent releases from tags
- Append an event entry
- Rotate a quote from a local list in repo (quotes.txt)
No external paid API. Public badges use open CDN endpoints from GitHub community tools.
-->
