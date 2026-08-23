<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=190&section=header&text=PIYUSH%20BADODE&fontSize=56&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20Engineer%20%E2%80%A2%20AI%2FML%20Builder%20%E2%80%A2%20System%20Designer&descAlignY=58&descColor=a78bfa&descSize=16"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2600&pause=900&color=A78BFA&center=true&vCenter=true&multiline=false&repeat=true&width=760&height=40&lines=Building+products%2C+not+just+projects.;MERN+%7C+AI%2FML+%7C+RAG+%7C+Microservices;Turning+ideas+into+production-ready+systems.;VJTI+Mumbai+%7C+Information+Technology;Voice+AI+%7C+Vapi.ai+%7C+LLMs+%7C+Gemini" alt="Typing SVG" />
</a>

<br/>

<a href="https://github.com/Piyush6046">
  <img src="https://img.shields.io/badge/GitHub-Piyush6046-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
</a>
&nbsp;
<a href="https://github.com/Piyush6046?tab=repositories">
  <img src="https://img.shields.io/badge/Repositories-23-302b63?style=for-the-badge&logo=github&logoColor=white"/>
</a>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=Piyush6046&style=for-the-badge&color=a78bfa&label=PROFILE+VIEWS"/>

</div>

<br/>

## About

```typescript
const piyush: Developer = {
  name        : "Piyush Badode",
  college     : "VJTI Mumbai — Information Technology",
  role        : ["Full-Stack Engineer", "AI/ML Builder", "System Designer"],
  languages   : ["C++", "TypeScript", "JavaScript", "Python", "SQL"],
  currentStack: {
    backend   : ["Node.js", "Express", "FastAPI", "Flask"],
    frontend  : ["React", "Vite", "Redux Toolkit", "Tailwind CSS"],
    database  : ["MongoDB", "MySQL"],
    ai_ml     : ["Gemini", "OpenAI", "Vapi.ai", "XGBoost", "SHAP", "RAG"],
    cloud     : ["Vercel", "Render", "MongoDB Atlas", "Cloudinary"],
    payments  : ["Razorpay"],
  },
  mindset     : "Problem → Architecture → Data Flow → Scale",
  philosophy  : "Build for the problem, not for the technology",
  currentlyExploring: ["Advanced RAG", "Agentic AI", "Distributed Systems", "MLOps", "Redis"],
};
```

> *"I don't build pages. I build systems — where data flows, AI reasons, and scale is a design decision."*

<br/>

## Engineering Universe

<div align="center">

| Full-Stack | AI / ML | Systems | CS Fundamentals |
|:---|:---|:---|:---|
| React / Vite | Generative AI | Microservices | Data Structures |
| Node.js / Express | RAG Pipelines | FastAPI / Flask | Algorithms & DP |
| MongoDB / MySQL | LLM Applications | API Architecture | DBMS / SQL |
| Redux Toolkit | Gemini / OpenAI | Database Design | OOP Principles |
| JWT / Cookies | Vapi.ai (Voice AI) | Caching Strategies | OS / CN |
| Razorpay | XGBoost / RF / LR | Webhooks | System Design |
| Cloudinary | SHAP Explainability | Authentication | Problem Solving |
| REST API Design | Scikit-learn | Deployment Pipelines | Software Engineering |

</div>

<br/>

## Technology Arsenal

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=cpp,python,javascript,typescript,html,css,sql&theme=dark" />

**Backend**
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,flask&theme=dark" />

**Frontend**
<br/>
<img src="https://skillicons.dev/icons?i=react,vite,tailwind,redux&theme=dark" />

**Database & Cloud**
<br/>
<img src="https://skillicons.dev/icons?i=mongodb,mysql,vercel,render,cloudflare&theme=dark" />

**AI / ML**
<br/>
<img src="https://skillicons.dev/icons?i=python,pytorch,sklearn&theme=dark" />

**Tools**
<br/>
<img src="https://skillicons.dev/icons?i=git,github,vscode,postman,linux&theme=dark" />

<br/>

## Featured Projects

---

### 01 — InstructoPlus | AI-Powered LMS

> **AI-Powered MERN Learning Management System** — full-stack LMS with AI-generated lecture notes, an AI tutor over ingested course content, YouTube-based lecture creation, and a complete payments pipeline.

```mermaid
flowchart LR
    A["YouTube Playlist"] --> B["Lecture Creation"]
    B --> C["Content Chunking"]
    C --> D{"Gemini AI"}
    D -->|Generate| E["AI Lecture Notes"]
    D -->|Answer| F["RAG-lite Tutor"]
    F --> G["Student Question"]
    G --> H["Relevant Context"]
    H --> D

    style A fill:#1e1b4b,color:#a78bfa,stroke:#a78bfa
    style D fill:#7c3aed,color:#fff,stroke:#a78bfa
    style E fill:#1e1b4b,color:#34d399,stroke:#34d399
    style F fill:#1e1b4b,color:#f59e0b,stroke:#f59e0b
```

**Payment flow:** `Client → Create Order → Backend → Razorpay → HMAC-SHA256 Signature Verification → Confirmed`

**Data design:** compound index `(userId, courseId)` prevents duplicate course-progress records.

| Layer | Technology |
|---|---|
| Frontend | React + Vite |
| Backend | Node.js + Express |
| Auth | JWT + httpOnly Cookies |
| AI | Gemini + RAG-lite |
| Queues | Redis + BullMQ (email) |
| Payment | Razorpay + server-side verification |
| Storage | MongoDB + Cloudinary |
| Deploy | Vercel + Render + MongoDB Atlas + Docker |

<div align="center">
<img src="https://img.shields.io/badge/AI-Powered-7c3aed?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG-Lite-0891b2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Payments-Razorpay-02042b?style=for-the-badge&logo=razorpay&logoColor=white"/>
<img src="https://img.shields.io/badge/MERN-Stack-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
</div>

**Repo:** [InstructoPlus](https://github.com/Piyush6046/InstructoPlus)

---

### 02 — UniBuddy | AI Student Ecosystem

> **AI-Powered Student Ecosystem** — a single platform for campus life, academics, career prep and student services, built around a voice-driven AI mock interviewer.

```mermaid
flowchart TD
    A["Resume PDF"] --> B["Resume Parser (Affinda)"]
    B --> C["Candidate Profile"]
    D["Job Description"] --> E{"AI Interview Engine"}
    C --> E
    E --> F["Voice Conversation (Vapi.ai / WebRTC)"]
    F --> G["Interview Transcript"]
    G --> H["AI Evaluation"]
    H --> I["Technical Score"]
    H --> J["Communication Score"]
    H --> K["Overall Score"]
    I --> L["Detailed Feedback Report"]
    J --> L
    K --> L

    style E fill:#065f46,color:#34d399,stroke:#34d399
    style F fill:#1e3a5f,color:#60a5fa,stroke:#60a5fa
    style L fill:#1c1917,color:#f59e0b,stroke:#f59e0b
```

**Campus ecosystem modules**

| Module | Purpose |
|---|---|
| AI Mock Interviewer | Voice-to-voice placement prep with resume-aware questions |
| Hostel Management | Campus accommodation |
| Food Discovery | Canteen / food services |
| Mentorship | Senior / alumni connections |
| Marketplace | Student book exchange |
| Pointer Helper | SGPA/CGPA tracking + target prediction |
| Admin Panel | Platform management |

<div align="center">
<img src="https://img.shields.io/badge/Voice_AI-Vapi.ai-8b5cf6?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Resume_Parse-Affinda-0ea5e9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/State-Redux_Toolkit-ff6edb?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AI-OpenAI+Gemini-10b981?style=for-the-badge"/>
</div>

**Repo:** [UniBuddy-Deployment](https://github.com/Piyush6046/UniBuddy-Deployment)

---

### 03 — TeleRetain | Churn Prediction SaaS

> **AI-Powered Telecom Customer Retention Platform** — full-stack SaaS predicting churn with an ML ensemble, and turning predictions into explainable retention decisions via SHAP.

```mermaid
flowchart LR
    A["React + Vite"] -->|Axios| B["Node.js + Express"]
    B -->|Mongo Driver| C[("MongoDB")]
    B -->|Axios| D["Python FastAPI"]
    D --> E["Logistic Regression"]
    D --> F["Random Forest"]
    D --> G["XGBoost"]
    F -->|Prediction| H["SHAP Explainer"]
    G -->|Prediction| H
    H --> I["Business Insights"]

    style D fill:#1a1a2e,color:#f472b6,stroke:#f472b6
    style F fill:#16213e,color:#f59e0b,stroke:#f59e0b
    style H fill:#0f3460,color:#34d399,stroke:#34d399
```

**Model leaderboard**

| Model | ROC-AUC | F1 | Precision | Recall |
|---|---|---|---|---|
| Random Forest (deployed) | **0.85** | **0.65** | **0.56** | **0.78** |
| Logistic Regression | 0.86 | 0.64 | 0.52 | 0.84 |
| XGBoost | 0.85 | 0.63 | 0.55 | 0.75 |

**Explainable AI** — instead of just `Churn = 82%`, the system answers *why*:

```
Contract Duration    ─────────────────►  HIGH RISK   (+++)
Monthly Charges      ──────────────►    RISK         (++)
Tenure                ◄────────────      PROTECTION   (--)
Support Services      ◄───────────       PROTECTION   (--)
```

<div align="center">
<img src="https://img.shields.io/badge/SHAP-Explainability-f472b6?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Microservices-FastAPI-009688?style=for-the-badge&logo=fastapi"/>
<img src="https://img.shields.io/badge/ML_Ensemble-XGB+RF+LR-f59e0b?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LLM-Groq-1f2937?style=for-the-badge"/>
</div>

**Repo:** [TeleRetain](https://github.com/Piyush6046/TeleRetain)

---

### 04 — TradePlus AI | Intelligent Trade Matchmaking

> **Intelligent Import–Export Matchmaking** — an ML pipeline generating 23,815 exporter–importer pairs, engineering 34 features, and producing explainable match scores with XGBoost + SHAP. Built at LOC Hackathon (top 5 of ~30 teams, team of four, two-day build).

```mermaid
flowchart TD
    A["Raw CSV Data"] --> B["Pair Generation<br/>23,815 pairs"]
    B --> C["Feature Engineering<br/>34 features"]
    C --> D{"Model Training"}
    D --> E["XGBoost (best)"]
    D --> F["LightGBM"]
    D --> G["Random Forest"]
    D --> H["Logistic Regression"]
    E --> I["SHAP Explainability"]
    I --> J["Match + Reason"]

    style E fill:#1e3a5f,color:#60a5fa,stroke:#60a5fa
    style I fill:#1e1b4b,color:#a78bfa,stroke:#a78bfa
    style J fill:#065f46,color:#34d399,stroke:#34d399
```

**Best model — XGBoost**

```
ROC-AUC       →  0.9802
Accuracy      →  97.63%
Precision     →  97.96%
Recall        →  99.55%
F1 Score      →  0.9875
5-Fold AUC    →  0.9755 ± 0.0047
```

**Feature engineering covers:** capacity ratio, geographic alignment, trade corridors, logistics compatibility, regulatory alignment, payment terms, hiring signals, tariff exposure, geopolitical and war risk.

**Architecture:** `React → Node.js API → Feature Builder → Python Flask ML → XGBoost + SHAP → Match + Explanation`

<div align="center">
<img src="https://img.shields.io/badge/XGBoost-0.9802_AUC-f59e0b?style=for-the-badge"/>
<img src="https://img.shields.io/badge/34_Features-Engineered-60a5fa?style=for-the-badge"/>
<img src="https://img.shields.io/badge/SHAP-Explained-a78bfa?style=for-the-badge"/>
<img src="https://img.shields.io/badge/23815_Pairs-Generated-34d399?style=for-the-badge"/>
</div>

**Repo:** [tradeplus-ai](https://github.com/Piyush6046/tradeplus-ai)

---

### 05 — VAPT | Web Application Security

> **Vulnerability Assessment & Penetration Testing** — looking at applications not just as *"how do I build it?"* but *"how can this system fail, and how do I protect it?"*

| Domain | Focus Area |
|---|---|
| Authentication | Access control, session management |
| Authorization | Privilege escalation, role violations |
| Injection | SQLi, XSS, command injection |
| Input Validation | Boundary conditions, type coercion |
| HMAC / Signature | Cryptographic verification |

**Repo:** [VAPT](https://github.com/Piyush6046/VAPT)

---

### 06 — Digital Heroes | Golf Charity Platform

> **Subscription + Golf Scores + Monthly Draw + Charity + Admin** — a full-stack product specification for a charity lottery system with golf-handicap logic.

```mermaid
flowchart LR
    A["Subscriber"] --> B["Enter Last 5 Scores"]
    B --> C["Monthly Draw"]
    C -->|3-Number Match| D["25% of Pool"]
    C -->|4-Number Match| E["35% of Pool"]
    C -->|5-Number Match| F["40% of Pool — Jackpot"]
    F -->|Unclaimed| G["Rollover"]

    style F fill:#1c1917,color:#f59e0b,stroke:#f59e0b
    style G fill:#1c1917,color:#ef4444,stroke:#ef4444
```

**Admin capabilities:** users, subscriptions, draw configuration, draw simulation, charity management, winner verification, payouts, analytics.

<br/>

## Other Builds

<div align="center">

| Project | Focus | Stack |
|---|---|---|
| **Quiz App** | Interactive quiz platform | HTML / CSS / JS |
| **VJTI Books** | Student book platform | JavaScript |
| **Movie Management** | Movie/show booking & billing | MySQL |
| **Online Library** | Library management system | Web |
| **SGPA Calculator** | Academic grade predictor | TypeScript |
| **Image Denoising** | Image processing / ML | Python |
| **GameZone** | Browser gaming platform | HTML |
| **Portfolio** | Personal portfolio site | HTML / CSS |

</div>

<br/>

## Engineering Principles

| Principle | Description |
|:---|---|
| **Problem First** | *What is the problem?* always precedes *what technology should I use?* |
| **Separation of Concerns** | Frontend ↔ API Layer ↔ Business Logic ↔ Database ↔ AI/ML Services |
| **Explainable AI** | `Prediction + Reason + Evidence` beats `Prediction only` |
| **Beyond the Happy Path** | Auth failures, payment verification, API fallbacks, model failures, scale |
| **Data-Driven Design** | Schema, indexing, and compound constraints are first-class decisions |
| **Build for Scale** | Every design decision considers what happens when the system grows |

```text
IDEA → PROBLEM → REQUIREMENTS → ARCHITECTURE → [FRONTEND · BACKEND · DATA/AI] → TEST → DEPLOY → SCALE
```

<br/>

## Developer Journey

```mermaid
timeline
    title Piyush Badode — Engineering Timeline
    2023 : Started engineering journey
         : Foundations of CS
    2024 : Web development
         : JavaScript & React
         : SQL & DSA
         : Core engineering
    2025 : MERN stack mastery
         : Machine learning
         : Image processing
         : Full-stack production projects
    2026 : AI applications & RAG
         : Voice AI (Vapi.ai)
         : Microservices architecture
         : Explainable ML (SHAP)
         : System design
    Next : Distributed systems
         : Advanced AI systems
         : Cloud architecture
         : Building at scale
```

<br/>

## GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Piyush6046&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=c9d1d9&border_radius=10"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Piyush6046&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9&border_radius=10"/>

<br/><br/>

<img width="70%" src="https://streak-stats.demolab.com?user=Piyush6046&theme=tokyonight&hide_border=true&background=0d1117&stroke=a78bfa&ring=a78bfa&fire=f59e0b&currStreakLabel=a78bfa&border_radius=10"/>

<br/><br/>

<img width="90%" src="https://github-profile-trophy.vercel.app/?username=Piyush6046&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7"/>

</div>

<br/>

## Contribution Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Piyush6046/Piyush6046/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Piyush6046/Piyush6046/output/github-contribution-grid-snake.svg"/>
  <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/Piyush6046/Piyush6046/output/github-contribution-grid-snake.svg"/>
</picture>

</div>

<br/>

## Currently Exploring

<div align="center">

| Area | Focus |
|:---|:---|
| Advanced RAG | Building smarter retrieval systems |
| Agentic AI | Multi-step autonomous LLM agents |
| Distributed Systems | CAP theorem, consistency patterns |
| Redis & Caching | Pub/sub, sessions, rate limiting |
| Cloud Architecture | IaC, serverless, edge computing |
| App Security | Threat modeling, secure SDLC |
| MLOps | Model versioning, drift detection |
| Docker & Kubernetes | Container orchestration at scale |

</div>

<br/>

## Featured Repositories

<div align="center">

<a href="https://github.com/Piyush6046/UniBuddy-Deployment">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Piyush6046&repo=UniBuddy-Deployment&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&border_radius=10"/>
</a>
<a href="https://github.com/Piyush6046/InstructoPlus">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Piyush6046&repo=InstructoPlus&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&border_radius=10"/>
</a>

<br/><br/>

<a href="https://github.com/Piyush6046/TeleRetain">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Piyush6046&repo=TeleRetain&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=f472b6&icon_color=f472b6&border_radius=10"/>
</a>
<a href="https://github.com/Piyush6046/tradeplus-ai">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Piyush6046&repo=tradeplus-ai&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=60a5fa&icon_color=60a5fa&border_radius=10"/>
</a>

<br/><br/>

<a href="https://github.com/Piyush6046/VAPT">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Piyush6046&repo=VAPT&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=ef4444&icon_color=ef4444&border_radius=10"/>
</a>

</div>

<br/>

<div align="center">

## Let's Connect

<a href="https://github.com/Piyush6046">
  <img src="https://img.shields.io/badge/GitHub-Piyush6046-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
</a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=700&lines=Code+%E2%86%92+Build+%E2%86%92+Break+%E2%86%92+Learn+%E2%86%92+Improve+%E2%86%92+Repeat;Build+for+the+problem%2C+not+for+the+technology." alt="Footer typing"/>

<br/>

**Thanks for visiting — if something here resonated, leave a star on a repo that helped you.**

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=110&section=footer"/>

</div>
