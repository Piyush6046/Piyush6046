<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:1a0a2e,70:2d1b69,100:6e40c9&height=180&section=header&text=Piyush%20Badode&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Information%20Technology%20%C2%B7%20VJTI%20Mumbai&descAlignY=58&descColor=a78bfa&descSize=17"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2600&pause=900&color=A78BFA&center=true&vCenter=true&width=750&lines=Building+full-stack+systems+and+AI+applications.;Voice+AI+%C2%B7+RAG+%C2%B7+LLM+workflows+%C2%B7+Matching+engines.;MERN+%C2%B7+Python+%C2%B7+TypeScript+%C2%B7+Gemini+%C2%B7+Vapi.ai;Engineering+at+VJTI+Mumbai+%C2%B7+Information+Technology." alt="Typing SVG"/>
</a>

<br/><br/>

[![GitHub](https://img.shields.io/badge/github-Piyush6046-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Piyush6046)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Piyush_Badode-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/piyush-badode-058a9b291/)
&nbsp;
[![UniBuddy Live](https://img.shields.io/badge/🌐_UniBuddy-Live-10b981?style=for-the-badge)](https://unibuddy-frontend.netlify.app/home)
&nbsp;
[![Profile Views](https://komarev.com/ghpvc/?username=Piyush6046&style=for-the-badge&color=6e40c9&label=VIEWS)](https://github.com/Piyush6046)

</div>

---

## `$ whoami`

```typescript
const piyush = {
  education   : "Information Technology · VJTI Mumbai",
  building    : ["full-stack systems", "AI-powered apps", "intelligent matching"],
  aiStack     : ["Gemini 2.0", "GPT-4o-mini", "Vapi.ai", "RAG-lite", "SHAP"],
  backendStack: ["Node.js", "Express", "FastAPI", "MongoDB", "JWT"],
  exploring   : ["agentic AI", "advanced RAG", "system design", "MLOps"],
  languages   : ["TypeScript", "JavaScript", "Python", "C++", "SQL"],
  currently   : "integrating AI into full-stack systems that solve real problems",
};
```

> Five projects. Five engineering dimensions. One trajectory: **software systems → intelligent systems.**

---

## What I Build

<div align="center">

| 🖥️ Full-Stack Systems | 🤖 AI / GenAI Applications | ⚙️ Backend & Data |
|:---:|:---:|:---:|
| MERN applications | LLM-powered workflows | REST API design |
| React + TypeScript UIs | Voice AI (Vapi.ai + WebRTC) | MongoDB · MySQL |
| SaaS-style dashboards | Resume parsing pipelines | JWT · httpOnly cookies |
| Authentication systems | RAG-lite & contextual AI | Payment verification |
| Real-time features | AI interview & tutor systems | Microservice architecture |
| Deployment pipelines | Custom scoring/ranking engines | Data modelling & indexing |

</div>

---

## Featured Systems

---

### `01` · UniBuddy — AI-Powered Student Ecosystem

<div align="center">

[![Repo](https://img.shields.io/badge/GitHub-UniBuddy--Deployment-0d1117?style=flat-square&logo=github&logoColor=white)](https://github.com/Piyush6046/UniBuddy-Deployment)
&nbsp;
[![Live](https://img.shields.io/badge/🌐_Live-unibuddy.netlify.app-10b981?style=flat-square)](https://unibuddy-frontend.netlify.app/home)
&nbsp;
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Node](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white)

</div>

A campus platform where the real challenge was building an **end-to-end AI mock interview system** — resume parsing → voice conversation → LLM evaluation → scored feedback — all persisted and replayable.

<details>
<summary><b>⚡ Architecture — AI Mock Interview Pipeline</b></summary>

<br/>

```mermaid
flowchart TD
    A([📄 Resume PDF]) --> B[Affinda Resume Parser]
    B --> C[(Structured Candidate Profile)]
    C --> D[AI Interview Configuration]
    D --> E{🎙️ Vapi.ai}
    E -->|LLM Brain| F[GPT-4o-mini]
    E -->|Voice Channel| G[WebRTC Session]
    G --> H[Interview Conversation]
    H --> I[Post-call Webhook]
    I --> J[Node.js Backend]
    J --> K[(MongoDB)]
    K --> L([📊 Scores · Feedback · History])

    style A fill:#1a0a2e,color:#a78bfa,stroke:#6e40c9
    style E fill:#0d2d1a,color:#34d399,stroke:#10b981
    style F fill:#1a1a0d,color:#fbbf24,stroke:#f59e0b
    style J fill:#1a0a0a,color:#f87171,stroke:#ef4444
    style K fill:#0a1a2d,color:#60a5fa,stroke:#3b82f6
    style L fill:#1a0a2e,color:#a78bfa,stroke:#6e40c9
```

</details>

<details>
<summary><b>🏫 Platform Modules</b></summary>

<br/>

| Module | Description |
|---|---|
| 🎤 AI Mock Interviewer | Voice-based · Resume-aware · LLM-evaluated |
| 📊 Grade Analytics | SGPA / CGPA calculation and tracking |
| 📚 Book Marketplace | Buy / sell campus books |
| 💬 Community Chat | Campus-wide messaging |
| 👤 Profile Management | Student identity and interview history |
| 🔐 Admin Panel | Platform oversight and management |

</details>

**Engineering decisions worth noting:**

- Webhook-driven post-call processing — interview is async, evaluation fires server-side after Vapi callback
- Score persistence in MongoDB — not ephemeral, full interview history available
- Resume parsing fully decoupled from interview session

**Stack:** `React` · `TypeScript` · `Tailwind CSS` · `Redux Toolkit` · `Node.js` · `Express` · `MongoDB` · `Vapi.ai` · `GPT-4o-mini` · `Affinda` · `WebRTC`

---

### `02` · InstructoPlus — AI-Powered Learning Management System

<div align="center">

[![Repo](https://img.shields.io/badge/GitHub-InstructoPlus-0d1117?style=flat-square&logo=github&logoColor=white)](https://github.com/Piyush6046/InstructoPlus)
&nbsp;
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-02042B?style=flat-square&logo=razorpay&logoColor=3395FF)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

</div>

A MERN LMS where educators import YouTube playlists as course content and Gemini generates lecture notes on demand. The challenge was combining AI content generation, server-side payment verification, and progress persistence in one coherent system.

<details>
<summary><b>🤖 AI Content Pipeline</b></summary>

<br/>

```mermaid
flowchart LR
    A([🎬 YouTube Playlist]) --> B[Lecture Import]
    B --> C[Content Extraction]
    C --> D{Gemini LLM}
    D -->|Generate| E[📝 AI Lecture Notes]
    D -->|Answer Q&A| F[🤖 AI Tutor]
    E --> G[(MongoDB Cache)]
    G -->|Cached hit| H([Student View])
    F --> H

    style A fill:#1a0d00,color:#fb923c,stroke:#f97316
    style D fill:#0d1a2e,color:#60a5fa,stroke:#3b82f6
    style E fill:#0d1a0d,color:#4ade80,stroke:#22c55e
    style F fill:#1a0d1a,color:#c084fc,stroke:#a855f7
    style G fill:#0a1a2d,color:#60a5fa,stroke:#3b82f6
```

</details>

<details>
<summary><b>💳 Payment Verification Flow</b></summary>

<br/>

```mermaid
sequenceDiagram
    participant C as Client
    participant B as Backend
    participant R as Razorpay

    C->>B: Create Order Request
    B->>R: Initialize Order
    R-->>B: Order ID
    B-->>C: Order ID
    C->>R: Payment (Card/UPI)
    R-->>C: Payment + Signature
    C->>B: Signature Verification Request
    B->>B: HMAC-SHA256 Verify
    B-->>C: ✅ Course Unlocked
```

> Server-side verification — the backend validates the HMAC signature before granting course access. Client trust is never assumed.

</details>

<details>
<summary><b>📦 Data Design</b></summary>

<br/>

Course progress uses a compound uniqueness constraint on `(userId, courseId)` — preventing duplicate progress documents while enabling efficient per-student queries at any scale.

</details>

**Deployment:** `Vercel` (frontend) · `Render` (backend) · `MongoDB Atlas`

**Stack:** `React` · `Node.js` · `Express` · `MongoDB` · `Google Gemini` · `JWT` · `Cloudinary` · `Razorpay`

---

### `03` · TeleRetain — Churn Prediction & Retention Platform

<div align="center">

[![Repo](https://img.shields.io/badge/GitHub-TeleRetain-0d1117?style=flat-square&logo=github&logoColor=white)](https://github.com/Piyush6046/TeleRetain)
&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi)
![Node](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-Explainability-6e40c9?style=flat-square)

</div>

A monorepo platform putting ML into a backend context — not just training a model, but building a system where predictions flow from model to dashboard to actionable business decisions.

<details>
<summary><b>🏗️ Monorepo Service Architecture</b></summary>

<br/>

```mermaid
flowchart TD
    A([⚛️ React Frontend]) --> B[Node.js / Express API\n/backend]
    B --> C[(MongoDB\nCustomer Data)]
    B -->|ML Request| D[Python FastAPI\n/ml-service]
    D --> E{Model Selection}
    E --> F[Logistic Regression]
    E --> G[🌲 Random Forest ⭐ Default]
    E --> H[⚡ XGBoost]
    G --> I[SHAP Explainer]
    I --> J([💡 Prediction + Business Reason])

    style A fill:#0d1a2e,color:#60a5fa,stroke:#3b82f6
    style B fill:#0d2d1a,color:#34d399,stroke:#10b981
    style D fill:#1a0d00,color:#fb923c,stroke:#f97316
    style G fill:#0d2d1a,color:#34d399,stroke:#10b981
    style I fill:#1a0a2e,color:#a78bfa,stroke:#6e40c9
    style J fill:#0d1a0d,color:#4ade80,stroke:#22c55e
```

</details>

<details>
<summary><b>📊 Model Comparison</b></summary>

<br/>

| Model | ROC-AUC | F1 | Note |
|---|---|---|---|
| Logistic Regression | 0.86 | 0.64 | Baseline |
| **Random Forest** ⭐ | **0.85** | **0.65** | **Default · Best F1** |
| XGBoost | 0.85 | 0.63 | Alternative |

The ML service returns a SHAP-based explanation alongside each prediction — so the business understands *why* a customer is at risk, not just that they are.

</details>

**Stack:** `React` · `Node.js` · `Express` · `MongoDB` · `Python` · `FastAPI` · `XGBoost` · `Scikit-learn` · `SHAP`

---

### `04` · TradePlus AI — Intelligent B2B Trade Matchmaking

<div align="center">

[![Repo](https://img.shields.io/badge/GitHub-tradeplus--ai-0d1117?style=flat-square&logo=github&logoColor=white)](https://github.com/Piyush6046/tradeplus-ai)
&nbsp;
![Hackathon](https://img.shields.io/badge/🏆_Hackathon-6e40c9?style=flat-square)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Gemini](https://img.shields.io/badge/Gemini_2.0_Flash-4285F4?style=flat-square&logo=google&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)

</div>

A full-stack B2B trade matchmaking platform where the core intelligence is **TradeCupid** — a custom 9-dimensional weighted scoring engine (prototyped in Python, implemented in Node.js) that ranks trade opportunities across a dataset of 5,000+ importers/exporters.

<details>
<summary><b>⚙️ TradeCupid Matching Engine</b></summary>

<br/>

```mermaid
flowchart TD
    A([📂 CSV Trade Dataset\n5,000+ leads]) --> B[Data Hydration]
    B --> C{TradeCupid Engine}

    C --> D1[Demand Fit]
    C --> D2[Geo-Fit]
    C --> D3[Behavioral Fit]
    C --> D4[Reliability]
    C --> D5[Scale Fit]
    C --> D6[Safety / Risk]
    C --> D7[Industry Compatibility]
    C --> D8[Trade Corridors]
    C --> D9[Firmographic Signals]

    D1 & D2 & D3 & D4 & D5 & D6 & D7 & D8 & D9 --> E[Weighted Match Score\n0 – 100]
    E --> F[Ranked Trade Opportunities]
    F --> G{Gemini 2.0 Flash}
    G -->|Reasoning| H[AI Match Explanation]
    G -->|Generate| I[Partner SWOT Analysis]
    G -->|Compose| J[Autonomous Outreach Message]
    H & I & J --> K([🎯 Match Hunter Dashboard])

    style A fill:#0a1a2d,color:#60a5fa,stroke:#3b82f6
    style C fill:#1a0a2e,color:#a78bfa,stroke:#6e40c9
    style E fill:#1a1a0d,color:#fbbf24,stroke:#f59e0b
    style G fill:#0d1a0d,color:#4ade80,stroke:#22c55e
    style K fill:#1a0d00,color:#fb923c,stroke:#f97316
```

</details>

<details>
<summary><b>🌐 Platform Features</b></summary>

<br/>

| Feature | Description |
|---|---|
| 🎯 Match Hunter | Discovery dashboard with ranked trade opportunities |
| ⚙️ TradeCupid Engine | Custom 9-dimensional weighted scoring |
| 🧠 AI Reasoning | Gemini-powered match explanations + partner insights |
| 🔬 Algorithm Lab | Interactive visualization of scoring vectors and AI reasoning |
| 📩 Autonomous Outreach | AI-generated first-contact messages on interest expressed |
| 📅 Trade Calendar | Scheduling and interaction tracking |
| 🎥 Video Conferencing | Jitsi-based in-platform video calls |
| 💬 AI Chatbot | Trade-related AI assistant |

</details>

**What makes it interesting:** The scoring is transparent and inspectable — the Algorithm Lab UI shows exactly which signals drove a match score and why. Intelligence without the black box.

**Stack:** `React` · `Node.js` · `Express` · `MongoDB` · `Gemini 2.0 Flash` · `Framer Motion` · `Python` (prototype) · `Jitsi`

---

### `05` · VAPT — Web Application Vulnerability Scanner

<div align="center">

[![Repo](https://img.shields.io/badge/GitHub-VAPT-0d1117?style=flat-square&logo=github&logoColor=white)](https://github.com/Piyush6046/VAPT)
&nbsp;
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Security](https://img.shields.io/badge/Security-Scanning-ef4444?style=flat-square)
![VAPT](https://img.shields.io/badge/Full_Stack-VAPT-6e40c9?style=flat-square)

</div>

A full-stack vulnerability assessment tool — frontend dashboard + backend scanning system — that scans live target URLs for web application vulnerabilities including SQL injection and XSS.

<details>
<summary><b>🛡️ Scanning Architecture</b></summary>

<br/>

```mermaid
flowchart TD
    A([🌐 Target URL Input]) --> B[Backend Scanner]
    B --> C{Probe Dispatch}
    C --> D[💉 SQL Injection\nProbes]
    C --> E[🔀 XSS Detection\nProbes]
    D --> F[Response Analysis]
    E --> F
    F --> G[Vulnerability Classification]
    G --> H[Risk Assessment]
    H --> I([📊 Frontend Dashboard\nFindings · Severity · Report])

    style A fill:#1a0a0a,color:#f87171,stroke:#ef4444
    style B fill:#1a0d00,color:#fb923c,stroke:#f97316
    style C fill:#1a1a0d,color:#fbbf24,stroke:#f59e0b
    style D fill:#1a0a0a,color:#f87171,stroke:#ef4444
    style E fill:#1a0a0a,color:#f87171,stroke:#ef4444
    style I fill:#0d1a0d,color:#4ade80,stroke:#22c55e
```

</details>

This project represents a different engineering axis — thinking about systems adversarially: not just *"does this work?"* but *"how can this break, and what does that expose?"*

**Stack:** `TypeScript` · `Full-stack frontend + backend scanning system`

---

## AI / GenAI

<div align="center">

### Built & Shipped

| Capability | Project |
|---|---|
| LLM integration — Gemini 2.0 Flash, GPT-4o-mini | TradePlus · InstructoPlus · UniBuddy |
| Voice AI — Vapi.ai + WebRTC voice sessions | UniBuddy AI Interviewer |
| Resume parsing — Affinda | UniBuddy |
| RAG-lite (context-injected LLM Q&A) | InstructoPlus AI Tutor |
| Webhook-driven async AI workflows | UniBuddy post-call processing |
| Autonomous AI output — outreach, SWOT, insights | TradePlus AI |
| Custom ranking / scoring engine | TradePlus TradeCupid |
| Explainable ML — SHAP feature importance | TeleRetain |
| AI content caching — no redundant LLM calls | InstructoPlus |

### Exploring

`Advanced RAG` · `Chunking + Embeddings + Vector Search` · `Agentic AI` · `Tool-calling` · `LangChain` · `MLOps` · `Model deployment`

</div>

---

## Tech Stack

<div align="center">

### Languages

<img src="https://skillicons.dev/icons?i=ts,js,python,cpp,html,css&theme=dark"/>

### Frontend

<img src="https://skillicons.dev/icons?i=react,tailwind,redux,vite&theme=dark"/>

### Backend

<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,flask&theme=dark"/>

### Databases & Cloud

<img src="https://skillicons.dev/icons?i=mongodb,mysql,vercel,netlify&theme=dark"/>

### Tools

<img src="https://skillicons.dev/icons?i=git,github,vscode,postman&theme=dark"/>

</div>

<br/>

<div align="center">

| Layer | Technologies |
|---|---|
| AI / GenAI | `Gemini 2.0 Flash` · `GPT-4o-mini` · `Vapi.ai` · `Affinda` |
| ML / Data | `XGBoost` · `Scikit-learn` · `SHAP` · `Pandas` |
| Auth & Payments | `JWT` · `httpOnly Cookies` · `Razorpay` · `HMAC-SHA256` |
| Media & Infra | `Cloudinary` · `Render` · `MongoDB Atlas` · `Jitsi` |

</div>

</div>

## GitHub Activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Piyush6046&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&title_color=a78bfa&icon_color=a78bfa&text_color=e6edf3&bg_color=0d1117"/>
&nbsp;
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Piyush6046&layout=compact&theme=github_dark&hide_border=true&title_color=a78bfa&text_color=e6edf3&bg_color=0d1117&langs_count=6"/>

<br/><br/>

<img width="65%" src="https://streak-stats.demolab.com?user=Piyush6046&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=6e40c9&ring=6e40c9&fire=f59e0b&currStreakLabel=a78bfa&sideNums=a78bfa&sideLabels=6b7280"/>

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=Piyush6046&theme=darkhub&no-frame=true&no-bg=true&row=1&column=7"/>

</div>

<br/>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Piyush6046/Piyush6046/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Piyush6046/Piyush6046/output/github-contribution-grid-snake.svg"/>
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/Piyush6046/Piyush6046/output/github-contribution-grid-snake.svg"/>
</picture>

</div>

<br/>

<div align="center">

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=Piyush6046&theme=react-dark&bg_color=0d1117&color=a78bfa&line=6e40c9&point=f59e0b&area=true&hide_border=true&area_color=6e40c9"/>

</div>

---

## LeetCode

<div align="center">

<img src="https://leetcard.jacoblin.cool/badodepiyush?theme=dark&font=JetBrains%20Mono&ext=heatmap&border=0&radius=12&site=com"/>

</div>

---

## Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Piyush6046-0d1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Piyush6046)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Piyush_Badode-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/piyush-badode-058a9b291/)
&nbsp;
[![LeetCode](https://img.shields.io/badge/LeetCode-badodepiyush-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/badodepiyush/)
&nbsp;
[![Email](https://img.shields.io/badge/Email-badodepiyush@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:badodepiyush@gmail.com)
&nbsp;

<br/>

<sub>VJTI Mumbai · Information Technology · Building at the intersection of software engineering and AI</sub>

</div>

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:6e40c9,50:2d1b69,100:0d1117&height=100&section=footer&animation=twinkling"/>
