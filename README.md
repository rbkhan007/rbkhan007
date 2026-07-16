<div align="center">

  <!-- TUI terminal hero -->
  <img src="assets/header.svg" alt="Rakibul Hasan — Full-Stack Developer & AI/LLM Specialist" width="100%" />

  <br/>

  <a href="mailto:rbkhan00009@gmail.com">
    <img src="https://img.shields.io/badge/STATUS-OPEN%20TO%20WORK-00FFAA?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Open to work" />
  </a>
  <img src="https://img.shields.io/badge/Remote-%F0%9F%8C%8D%20Worldwide-2088FF?style=for-the-badge" alt="Remote worldwide" />
  <img src="https://img.shields.io/badge/Based-Dhaka,%20BD-FF00AA?style=for-the-badge" alt="Based in Dhaka" />

</div>

<br/>

---

<br/>

## 👋 Hi, I'm Rakibul Hasan

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00FFAA&background=0D1117&center=true&vCenter=true&width=640&lines=Rhasan%40dev+%7C+Full-Stack+Developer;AI%2FLLM+Systems+%26+API+Orchestration;Production-Grade+Architecture+%26+DevOps;Open+to+Full-Time+%26+Contract+Roles" alt="Typing SVG" />
</div>

<br/>

<table>
  <tr>
    <td width="62%" valign="top">

A **results-driven Full-Stack Developer** who ships production-grade software from **database schema to polished UI**. I specialize in **AI/LLM systems, API orchestration, and cross-platform product design**, with a strong focus on security, performance, and scalable DevOps.

- 🎓 **B.Sc. in Computer Science & Engineering** — United International University (UIU)
- 🧠 **Focus:** RAG pipelines, LLM orchestration, API gateways, enterprise auth & security
- 🚀 **Currently:** Building **OllamoMUI**, an AI gateway emulating Ollama/OpenAI APIs
- 💼 **Looking for:** Full-Time Full-Stack / AI Engineering roles, DevOps automation, and high-scale contracts
- 📚 **Learning:** Agentic workflows, Edge AI, WebGPU, and advanced Kubernetes

    </td>
    <td width="38%" align="center">

<img src="assets/github-stats.svg" alt="GitHub Stats" width="100%" />

</td>
  </tr>
</table>

<br/>

## 📚 Currently Learning

<div align="center">

![Agentic Workflows](https://img.shields.io/badge/Agentic%20Workflows-00FFAA?style=for-the-badge&logo=openai&logoColor=white)
![Edge AI](https://img.shields.io/badge/Edge%20AI-2088FF?style=for-the-badge&logo=react&logoColor=white)
![WebGPU](https://img.shields.io/badge/WebGPU-FF00AA?style=for-the-badge&logo=webgpu&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

</div>

<br/>

---

<br/>

## 🧩 System Architecture

<div align="center">

```mermaid
flowchart TB
  Client[[🌐 Web / Desktop / Mobile Client]]:::client

  subgraph GW["🌐 API Gateway · OllamoMUI"]
    Auth[[🔐 PBKDF2 Auth + RBAC]]:::sec
    API[[⚡ Ollama / OpenAI-compatible API]]:::node
    Auth --> API
    API --> RAG[[🧠 RAG Pipeline]]:::node
  end

  subgraph DATA["🗄️ Data Layer"]
    PG[("PostgreSQL + pgvector")]:::db
    TRG[("pg_trgm Search")]:::db
    Cache[("Redis Cache")]:::db
  end

  Client -->|HTTPS| Auth
  RAG --> PG
  RAG --> TRG
  API --> Cache
  GW -->|SSRF-protected fetch| LLM{{"☁️ External LLM Provider"}}:::ext

  classDef client stroke:#58a6ff,stroke-width:2px,color:#58a6ff;
  classDef node stroke:#00FFAA,stroke-width:2px,color:#00FFAA;
  classDef sec stroke:#FF6B6B,stroke-width:2px,color:#FF6B6B;
  classDef db stroke:#2088FF,stroke-width:2px,color:#1f6feb;
  classDef ext stroke:#FF00AA,stroke-width:2px,color:#FF00AA;
```

</div>

<br/>

---

<br/>

## 🛠️ Tech Stack

<div align="center">

**Languages & Frontend**
<br/>
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=next.js&logoColor=white&style=for-the-badge)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?logo=react&logoColor=black&style=for-the-badge)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwind-css&logoColor=white&style=for-the-badge)
![Three.js](https://img.shields.io/badge/Three.js-black?logo=three.js&logoColor=white&style=for-the-badge)
<br/><br/>
**Backend, Data & AI**
<br/>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white&style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white&style=for-the-badge)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white&style=for-the-badge)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?logo=prisma&logoColor=white&style=for-the-badge)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white&style=for-the-badge)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge)
<br/><br/>
**DevOps & Security**
<br/>
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=github-actions&logoColor=white&style=for-the-badge)
![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white&style=for-the-badge)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white&style=for-the-badge)
![OAuth](https://img.shields.io/badge/OAuth%202.0-FF6B6B?style=for-the-badge)

</div>

<br/>

### 🗺️ Skills Map

<div align="center">

```mermaid
mindmap
  root((Rakibul<br/>Hasan))
    Frontend
      Next.js 15
      React Native
      TypeScript
      Tailwind CSS
      Three.js
    Backend
      Python
      FastAPI
      PostgreSQL
      pgvector
      Redis
    AI
      RAG Pipelines
      LLM Orchestration
      Technical SEO
    DevOps Sec
      Docker
      CI/CD
      Nginx
      RBAC
      OAuth
      HSTS
```

</div>

<br/>

---

<br/>

## 💼 Experience

| 🚀 Founder & Lead Developer — OllamoMUI | 💻 Full-Stack Developer — Freelance |
|:---|:---|
| *2025 — Present* | *2024 — Present* |
| • Built an **AI gateway** emulating Ollama/OpenAI APIs with **RAG** (pgvector / pg_trgm) | • Delivered **production web apps & AI integrations** for global clients |
| • Shipped **multi-platform clients** (Web, Desktop, Mobile) on a single backend | • Developed **RESTful services**, real-time dashboards, and secure auth flows |
| • Enforced enterprise security: **PBKDF2 auth, SSRF protection, audit logging** | • Integrated LLM pipelines, RAG search, and payment/automation systems |

<br/>

---

<br/>

## 🚀 Featured Projects

| 🤖 OllamoMUI | 🎓 GradBridge | 🖼️ ClippingBD Studio |
|:---:|:---:|:---:|
| *AI Gateway · FastAPI · pgvector* | *Education · Next.js · Supabase* | *Studio Platform · Vercel* |
| [![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/rbkhan007/OllamoMUI) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/rbkhan007/GradBridge) [![Live](https://img.shields.io/badge/Live-Site-00FFAA?style=flat-square)](https://grad-bridge-beta.vercel.app/) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/rbkhan007/ClippingBD-Studio) [![Live](https://img.shields.io/badge/Live-Site-00FFAA?style=flat-square)](https://clippingbdstudio.vercel.app/) |

<br/>

| 🎯 SiteSniper-AI | 🚀 Nexus-Crypto-Ventory | 🛍️ VeloCommerce-AI |
|:---:|:---:|:---:|
| *AI Analysis · Python* | *Crypto · TS · Prisma* | *Marketplace · AI* |
| [![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/rbkhan007/SiteSniper-AI) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/rbkhan007/Nexus-Crypto-Ventory) | [![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/rbkhan007/VeloCommerce-AI) |

<br/>

### 🔗 Project Map

<div align="center">

```mermaid
flowchart LR
  Me((Rakibul<br/>Hasan)):::me

  subgraph AI["AI / LLM"]
    OllamoMUI[OllamoMUI]:::p
    SiteSniper[SiteSniper-AI]:::p
    Velo[VeloCommerce-AI]:::p
  end

  subgraph WEB["Web / Platform"]
    Grad[GradBridge]:::p
    Clip[ClippingBD Studio]:::p
    Nexus[Nexus-Crypto-Ventory]:::p
  end

  Me --> OllamoMUI
  Me --> SiteSniper
  Me --> Velo
  Me --> Grad
  Me --> Clip
  Me --> Nexus

  classDef me stroke:#00FFAA,stroke-width:3px,color:#00FFAA;
  classDef p stroke:#2088FF,stroke-width:2px,color:#1f6feb;
```

</div>

<br/>

---

<br/>

## 🔄 DevOps & CI/CD Pipeline

<div align="center">

```mermaid
flowchart LR
  subgraph DEV["👨‍💻 Development"]
    A([Code Push]):::node
    B[[GitHub Repository]]:::node
  end

  subgraph CI["⚙️ CI Pipeline"]
    C[[GitHub Actions]]:::node --> D{Lint & Test Pass?}
    D -->|No| E([Notify Developer]):::fail
    D -->|Yes| F[[Build Docker Image]]:::node
  end

  subgraph CD["🚀 CD Pipeline"]
    G[[Push to Registry]]:::node --> H[[Deploy to Vercel / Cloud]]:::node
    H --> I([Production Ready]):::ok
  end

  A --> B --> C
  F --> G
  I -.->|Telemetry & Rollback| A

  classDef node stroke:#00FFAA,stroke-width:2px,color:#00FFAA;
  classDef ok stroke:#00FFAA,stroke-width:2px,color:#1a7f37;
  classDef fail stroke:#FF6B6B,stroke-width:2px,color:#cf222e;
```

</div>

<br/>

---

<br/>

## 📊 Skills & Activity

<!-- STATS:START -->
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=rbkhan007&show_icons=true&theme=transparent&hide_border=true&title_color=00FFAA&icon_color=00FFAA&text_color=8b949e&bg_color=0D1117" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rbkhan007&theme=dark&hide_border=true&background=0D1117&stroke=00FFAA&ring=00FFAA&fire=FF00AA&currStreakNum=00FFAA&sideNums=00FFAA&dates=8b949e" alt="Streak Stats" />
  <img src="https://img.shields.io/github/followers/rbkhan007?style=for-the-badge&logo=github&label=Followers&color=00FFAA" alt="Followers" />
  <img src="https://img.shields.io/github/stars/rbkhan007?style=for-the-badge&logo=github&label=Total%20Stars&color=FFD700" alt="Stars" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rbkhan007&layout=compact&theme=transparent&hide_border=true&title_color=00FFAA&text_color=8b949e&bg_color=0D1117" alt="Top Languages" />
</div>
<!-- STATS:END -->

<br/>

### 🐍 Contribution Snake

<div align="center">
  <img src="assets/snake.svg" alt="Contribution Snake" width="100%" />
</div>

<br/>

### 🌍 Visitor Map

<div align="center">
  <img src="https://visitcount.itsvg.in/?badge=1&icon=3&color=00FFAA&label=Visitors&style=flat-square" alt="Visitor Map" />
  <br/><br/>
  <img src="assets/profile-views.svg" alt="Profile Views" />
</div>

<div align="center">
  <table width="100%">
    <tr>
      <td width="50%"><img src="assets/skills-nextjs.svg" alt="Next.js 95%" /></td>
      <td width="50%"><img src="assets/skills-typescript.svg" alt="TypeScript 92%" /></td>
    </tr>
    <tr>
      <td width="50%"><img src="assets/skills-database.svg" alt="Database 90%" /></td>
      <td width="50%"><img src="assets/skills-threejs.svg" alt="Three.js 80%" /></td>
    </tr>
    <tr>
      <td width="50%"><img src="assets/skills-devops.svg" alt="DevOps 90%" /></td>
      <td width="50%"><img src="assets/skills-optimization.svg" alt="Optimization 98%" /></td>
    </tr>
  </table>
</div>

<br/>

  <table width="100%">
    <tr>
      <td colspan="2" align="center"><img width="100%" src="assets/activity-graph.svg" alt="Activity Graph" /></td>
    </tr>
  </table>

<br/>

---

<br/>

## 🏆 Achievements

<div align="center">

[![Followers](https://img.shields.io/github/followers/rbkhan007?style=for-the-badge&logo=github&label=Followers&color=00FFAA)](https://github.com/rbkhan007?tab=followers)
[![Total Stars](https://img.shields.io/github/stars/rbkhan007?style=for-the-badge&logo=github&label=Total%20Stars&color=FFD700)](https://github.com/rbkhan007?tab=repositories&sort=stargazers)
[![Commits/Week](https://img.shields.io/github/commit-activity/t/rbkhan007?style=for-the-badge&logo=git&label=Commits%2FWeek&color=2088FF)](https://github.com/rbkhan007?tab=repositories)
[![Public Repos](https://img.shields.io/github/repo-size/rbkhan007/rbkhan007?style=for-the-badge&logo=github&label=Repo%20Size&color=FF00AA)](https://github.com/rbkhan007/rbkhan007)
[![Last Commit](https://img.shields.io/github/last-commit/rbkhan007/rbkhan007?style=for-the-badge&logo=git&label=Last%20Commit&color=00CC88)](https://github.com/rbkhan007/rbkhan007)
[![Open Issues](https://img.shields.io/github/issues/rbkhan007?style=for-the-badge&logo=github&label=Open%20Issues&color=FF6B6B)](https://github.com/rbkhan007?tab=issues)

</div>

<br/>

---

<br/>

## 📬 Let's Work Together

<div align="center">

I'm actively looking for **full-time roles, contracts, and AI/DevOps collaborations**. The fastest way to reach me is email or LinkedIn.

<br/><br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?logo=google-chrome&logoColor=white&style=for-the-badge)](https://ollamomui.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/rakibul-hasan-khan-uiu/)
[![X (Twitter)](https://img.shields.io/badge/X-000000?logo=x&logoColor=white&style=for-the-badge)](https://twitter.com/Rakibulhas35269)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white&style=for-the-badge)](mailto:rbkhan00009@gmail.com)
[![Phone](https://img.shields.io/badge/Phone-%2B8801774471120-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+8801774471120)

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=rbkhan007&color=blueviolet&style=flat-square)

</div>

<br/>

---

<br/>

<div align="center">
  <img src="assets/footer.svg" alt="Footer" width="100%" />
  <br/><br/>
  <i><b>"Clean code + Relentless optimization + Robust DevOps = Flawless systems."</b></i>
</div>
