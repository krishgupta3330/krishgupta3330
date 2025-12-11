<!--
  README: Krish Gupta - Animated, crazy, eye-catching profile
  Paste this file into your GitHub profile repository README.md
  Replace any placeholder image URLs with your own screenshots/GIFs if desired.
-->

<!-- ========== Animated Header (inline SVG) ========== -->
<p align="center">
  <!-- Waving gradient text + floating orbs (SVG animation works on GitHub) -->
  <svg width="100%" height="220" viewBox="0 0 1200 220" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid meet">
    <defs>
      <linearGradient id="g1" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#00f0ff"/>
        <stop offset="50%" stop-color="#7f00ff"/>
        <stop offset="100%" stop-color="#ff0066"/>
      </linearGradient>
      <filter id="shadow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="8" result="b"/>
        <feOffset dx="0" dy="6" result="o"/>
        <feMerge><feMergeNode in="o"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
    </defs>

    <!-- Floating gradient blobs -->
    <g opacity="0.65">
      <circle cx="1100" cy="40" r="30" fill="url(#g1)">
        <animate attributeName="cy" dur="6s" values="40;20;40;60;40" repeatCount="indefinite" />
        <animate attributeName="cx" dur="8s" values="1100;1120;1080;1100" repeatCount="indefinite" />
      </circle>
      <circle cx="60" cy="60" r="24" fill="#ffd166">
        <animate attributeName="cy" dur="7s" values="60;40;80;60" repeatCount="indefinite" />
        <animate attributeName="cx" dur="9s" values="60;40;80;60" repeatCount="indefinite" />
      </circle>
      <circle cx="760" cy="160" r="18" fill="#06d6a0">
        <animate attributeName="cy" dur="5s" values="160;140;160;180;160" repeatCount="indefinite" />
        <animate attributeName="cx" dur="6s" values="760;780;740;760" repeatCount="indefinite" />
      </circle>
    </g>

    <!-- Main title with wave transform -->
    <g transform="translate(60,110)">
      <text font-family="Georgia, 'Times New Roman', serif" font-size="44" font-weight="800" fill="url(#g1)" filter="url(#shadow)">
        <tspan id="waveText">👋 Hi, I'm Krish Gupta — Data Scientist · Dev · AI Engineer</tspan>
      </text>

      <!-- Wavy animation by shifting y of tspan characters (SMIL) -->
      <g transform="translate(0,40)">
        <text font-family="Inter, Arial, sans-serif" font-size="16" fill="#8892b0">
          <tspan>Data Scientist • Data Analyst • Web & Full-Stack Developer</tspan>
        </text>
      </g>
    </g>

  </svg>
</p>

---

<!-- ========== Quick Links Badges ========== -->
<p align="center">
  <a href="https://teal-macaron-eb4b74.netlify.app/" target="_blank">📁 Portfolio</a> &nbsp; • &nbsp;
  <a href="https://yourneed-ai-brand-blueprint.vercel.app/" target="_blank">🎯 AI Brand Blueprint</a> &nbsp; • &nbsp;
  <a href="https://www.instagram.com/krish.nyx/?__pwa=1" target="_blank">📸 Instagram</a> &nbsp; • &nbsp;
  <a href="https://linkedin.com/in/krish-gupta-37b870337" target="_blank">💼 LinkedIn</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/krish965328%40gmail.com-email-blue?logo=gmail" alt="email" />
  <img src="https://img.shields.io/badge/Maharashtra-India-ff69b4" alt="location" />
  <img src="https://img.shields.io/badge/GitHub-KrishGupta3330-181717?logo=github" alt="github" />
</p>

---

# ✨ About Me
I build AI-first products, data systems, and full-stack web apps. I love turning chaotic data into clean, production-ready pipelines and building beautiful, usable interfaces.

- 🔭 Currently building: **AI-driven products & complex TypeScript systems**
- 🌱 Learning: Advanced ML model deployment & scalable infra
- 👯 Open to: Collaborations on AI, Data, and Web projects
- 📫 Reach me: **krish965328@gmail.com**

---

# 🛠 Tech Stack (live badges)
<p>
  <img src="https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black" alt="js" />&nbsp;
  <img src="https://img.shields.io/badge/TypeScript-0168C9?logo=typescript&logoColor=white" alt="ts" />&nbsp;
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="python" />&nbsp;
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black" alt="react" />&nbsp;
  <img src="https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white" alt="next" />&nbsp;
  <img src="https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=white" alt="node" />&nbsp;
  <img src="https://img.shields.io/badge/TypeScript-007ACC?logo=typescript" alt="ts2" />
</p>

---

# 🚀 Highlight Projects (animated cards)

> Tip: Replace the GIF/PNG links below with your own project GIFs/screenshots for maximum impact.

### ✨ Quantum-AI Drug Discovery Bot — Complete System
> AI pipeline & TypeScript orchestration for molecular screening, model-driven hypothesis generation and visualization.

![quantum-ai-demo](https://media.giphy.com/media/3o7aCRzPg8YyK8Xh7i/giphy.gif)
**Repo:** `quantum_ai_drug_discovery_bot_complete_system` • TypeScript • AI · Research · Visualization

---

### 🔐 TrustCheck AI - Guardian
> Security scanner & AI assistant for links, phone numbers and safety checks.

![trustcheck-demo](https://media.giphy.com/media/xT9IgG50Fb7Mi0prBC/giphy.gif)
**Repo:** `trustcheck-ai-guardian-24099` • TypeScript • Security · Automation

---

### 🎬 Cinemate-Rec
> Movie recommender with interactive UI and ML-powered suggestions.

![cinemate-demo](https://media.giphy.com/media/3o6gbbuLW76jkt8vIc/giphy.gif)
**Repo:** `cinemate-rec` • TypeScript • Recommender Systems

---

# 📚 Full Project Snapshot
Here are some top projects I maintain (copy to a project showcase section):

- `flash-usdt-sales` — Landing + GitHub Pages (HTML)
- `trustcheck-ai-guardian-24099` — Security AI (TypeScript)
- `cinemate-rec` — Recommender (TypeScript)
- `ai_climate_architect_application` — Climate AI (TypeScript)
- `yourneed-ai-brand-blueprint` — Brand generator (TypeScript)
- `quantum_ai_drug_discovery_bot_complete_system` — Quantum & AI + drug discovery (TypeScript)
- `Zero_Touch_Smart_Hospital_System` — Healthcare automation (TypeScript)
- `ai-legal-assistant-krish` — Legal assistant (TypeScript)
- `titan-ai-trader` — Trading agent (TypeScript)

👉 *Full repo list is in my GitHub profile.*

---

# 📊 GitHub Stats & Top Languages
<!-- These are dynamic images - replace username if you fork the README -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=krishgupta3330&show_icons=true&theme=radical&count_private=true" alt="Krish's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=krishgupta3330&layout=compact&theme=radical" alt="Top Languages" />
</p>

---

# 🔥 Skills — Visual Progress (SVG animated bars)
<p align="center">
  <!-- Inline SVG progress chart (animated) -->
  <svg width="680" height="150" viewBox="0 0 680 150" xmlns="http://www.w3.org/2000/svg">
    <!-- Background -->
    <rect width="680" height="150" fill="transparent"/>
    <!-- Skill 1 -->
    <text x="20" y="28" font-size="13" font-family="Arial" fill="#8892b0">Machine Learning</text>
    <rect x="20" y="36" width="640" height="18" rx="9" fill="#e6eef8"/>
    <rect x="20" y="36" width="0" height="18" rx="9" fill="#7f00ff">
      <animate attributeName="width" from="0" to="520" dur="1.8s" fill="freeze" />
    </rect>

    <!-- Skill 2 -->
    <text x="20" y="74" font-size="13" font-family="Arial" fill="#8892b0">Full-Stack Development</text>
    <rect x="20" y="82" width="640" height="18" rx="9" fill="#e6eef8"/>
    <rect x="20" y="82" width="0" height="18" rx="9" fill="#00f0ff">
      <animate attributeName="width" from="0" to="560" dur="1.9s" fill="freeze" />
    </rect>

    <!-- Skill 3 -->
    <text x="20" y="120" font-size="13" font-family="Arial" fill="#8892b0">AI Systems & Automation</text>
    <rect x="20" y="128" width="640" height="18" rx="9" fill="#e6eef8"/>
    <rect x="20" y="128" width="0" height="18" rx="9" fill="#ffd166">
      <animate attributeName="width" from="0" to="560" dur="2.0s" fill="freeze" />
    </rect>
  </svg>
</p>

---

# 🧭 How I Work
1. Understand product & objectives → Data collection → Modeling → UX & API → Deploy  
2. Focus on reproducible pipelines, readable code, and production-ready infra  
3. I love clean visuals and intuitive dashboards for complex models

---

# 🎯 What I’m Looking For
- Projects & collabs in **AI, Data, ML Ops, and Full-Stack**  
- Open to freelancing and long-term partnerships  
- Ping me if you want to co-build something wild 🚀

---

# 📬 Contact
- **Email:** krish965328@gmail.com  
- **Portfolio:** https://teal-macaron-eb4b74.netlify.app/  
- **AI Brand Blueprint:** https://yourneed-ai-brand-blueprint.vercel.app/  
- **Instagram:** https://www.instagram.com/krish.nyx/  
- **LinkedIn:** https://linkedin.com/in/krish-gupta-37b870337

---

# 🧩 Extras — Fun Widgets & Tips
- Add this to show your pinned repositories in a grid (replace with your repo list):
  ```md
  <!-- Pinned repo gifs/screenshots -->
  <p align="center">
    <a href="https://github.com/krishgupta3330/quantum_ai_drug_discovery_bot_complete_system">
      <img src="https://media.giphy.com/media/3o7aCSPqXE3YvK1i4k/giphy.gif" width="260" alt="Quantum-AI Demo" />
    </a>
    <a href="https://github.com/krishgupta3330/trustcheck-ai-guardian-24099">
      <img src="https://media.giphy.com/media/26xBP3pMZ1q9l4Qru/giphy.gif" width="260" alt="TrustCheck Demo" />
    </a>
  </p>
