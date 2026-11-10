 <div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:07111F,45:102A36,100:0F766E&height=230&section=header&text=Talha%20Belal&fontSize=68&fontColor=F0FDFA&fontAlignY=42&desc=SOFTWARE%20%7C%20AI%20%7C%20PRODUCT%20ENGINEERING&descSize=15&descAlignY=67&descColor=99F6E4" width="100%" alt="Talha Belal — Software, AI and Product Engineering" />

<br>

### Building useful technology. Turning ideas into products.

**CSE Undergraduate · Full-Stack Development · AI-Powered Applications**

<br>

<a href="https://linkedin.com/in/talha-belal-6a52371b6/">
  <img src="https://img.shields.io/badge/LINKEDIN-0B1727?style=for-the-badge&logo=linkedin&logoColor=67E8D2" alt="LinkedIn" />
</a>
<a href="mailto:talhabelal62@gmail.com">
  <img src="https://img.shields.io/badge/EMAIL-0B1727?style=for-the-badge&logo=gmail&logoColor=67E8D2" alt="Email" />
</a>
<a href="https://github.com/Talha0708">
  <img src="https://img.shields.io/badge/GITHUB-0B1727?style=for-the-badge&logo=github&logoColor=67E8D2" alt="GitHub" />
</a>

<br><br>

<a href="#selected-work">Selected Work</a> &nbsp; · &nbsp;
<a href="#engineering">Engineering</a> &nbsp; · &nbsp;
<a href="#technology">Technology</a> &nbsp; · &nbsp;
<a href="#github-activity">GitHub Activity</a> &nbsp; · &nbsp;
<a href="#connect">Connect</a>

</div>

---

## 01 — Profile

I'm a Computer Science & Engineering undergraduate at **Primeasia University**, interested in building practical software at the intersection of web technologies, artificial intelligence, and education.

I enjoy turning ideas into working products — from full-stack web applications and business automation systems to accessible learning platforms.

My approach is simple:

> **Understand the problem. Design the system. Build the solution. Improve through iteration.**

Currently exploring full-stack architecture, AI integrations, API-driven systems, and progressive web applications while strengthening my foundations in software engineering.

### Areas of Interest

| Area | What I'm Exploring |
|:---|:---|
| **Full-Stack Engineering** | React, Next.js, Node.js, backend architecture |
| **AI & Automation** | AI-powered workflows, chatbots, intelligent integrations |
| **Product Engineering** | SaaS platforms, CRM systems, business tools |
| **EdTech** | Interactive learning experiences and educational PWAs |
| **System Design** | API architecture, webhooks, data flow and application structure |

---

## 02 — Selected Work

*Ideas designed to solve real problems.*

### 🇩🇪 Banglay German

**Making German language learning accessible to Bengali speakers.**

<a href="https://banglaygerman.vercel.app/">
  <img src="https://img.shields.io/badge/EXPLORE_LIVE_PROJECT-0F766E?style=for-the-badge&logo=vercel&logoColor=white" alt="Explore Banglay German" />
</a>
<img src="https://img.shields.io/badge/PROGRESSIVE_WEB_APP-102A36?style=for-the-badge&logo=pwa&logoColor=67E8D2" alt="Progressive Web App" />

A structured German A1 learning platform designed around Bengali explanations, interactive practice, and memory-based revision.

**Inside the platform**

- 1,400+ vocabulary words across 10 learning units.
- 200+ everyday listening conversations.
- German article learning: der, die, das.
- SM-2-based spaced repetition for vocabulary revision.
- Interactive grammar, sentence-building, listening and typing exercises.
- Installable PWA with offline support.

**Product vision:** Make structured German learning more accessible to Bengali-speaking learners preparing for language examinations, Ausbildung, and higher education.

---

### 🗣️ Fluently

**A structured journey towards confident English communication.**

<a href="https://fluently-5juy.vercel.app/">
  <img src="https://img.shields.io/badge/EXPLORE_LIVE_PROJECT-0F766E?style=for-the-badge&logo=vercel&logoColor=white" alt="Explore Fluently" />
</a>
<img src="https://img.shields.io/badge/PWA-102A36?style=for-the-badge&logo=pwa&logoColor=67E8D2" alt="Progressive Web App" />

An interactive English-learning PWA built around a structured CEFR learning path.

**Key capabilities**

- 50 learning modules across A1, A2, B1, B2, and C1.
- Vocabulary development and memory-based revision.
- Voice-based learning practice.
- XP, achievements, level progression and daily goals.
- Personal learning dashboard and progress tracking.

**Product vision:** Turn independent language learning into a structured and engaging experience.

---

### ⚙️ Thirdwave CRM & AI Moderator

**Exploring intelligent customer communication and business automation.**

<a href="https://thirdwave-crm-cu8c.vercel.app/">
  <img src="https://img.shields.io/badge/VIEW_PROJECT-0F766E?style=for-the-badge&logo=vercel&logoColor=white" alt="View Thirdwave CRM" />
</a>
<img src="https://img.shields.io/badge/CRM_PROTOTYPE-102A36?style=for-the-badge&logo=probot&logoColor=67E8D2" alt="CRM Prototype" />

A CRM prototype exploring how AI can help businesses understand and organize incoming customer communications.

**Technical highlights**

- AI-assisted intent parsing for incoming messages.
- Meta Graph API integration.
- Webhook-based communication workflows.
- MongoDB-backed data handling.
- Next.js application architecture.

**Technology:** Next.js 14 · Node.js · MongoDB · Meta Graph API · Webhooks

---

## 03 — Engineering & System Thinking

*I am interested in understanding how software systems work beyond the user interface.*

### Thirdwave — Message Processing Architecture

```mermaid
flowchart TD
    A["Customer Message"] --> B["Meta / WhatsApp Webhook"]
    B --> C["Next.js API Layer"]
    C --> D["AI Intent Processing"]
    D --> E["MongoDB"]
    E --> F["CRM Dashboard"]

    style A fill:#102A36,stroke:#2DD4BF,color:#F0FDFA
    style B fill:#102A36,stroke:#2DD4BF,color:#F0FDFA
    style C fill:#102A36,stroke:#2DD4BF,color:#F0FDFA
    style D fill:#134E4A,stroke:#5EEAD4,color:#F0FDFA
    style E fill:#102A36,stroke:#2DD4BF,color:#F0FDFA
    style F fill:#102A36,stroke:#2DD4BF,color:#F0FDFA
```

The idea is to receive customer messages, process them through an API layer, identify intent using AI, and organize the resulting information inside a CRM.

### Banglay German — Spaced Repetition

```mermaid
flowchart TD
    A["Learn a New Word"] --> B["Scheduled Review"]
    B --> C{"Remembered?"}
    C -->|No| D["Review Again Sooner"]
    C -->|Yes| E["Increase Review Interval"]
    D --> F["Schedule Next Review"]
    E --> F
    F --> B

    style A fill:#102A36,stroke:#2DD4BF,color:#F0FDFA
    style B fill:#102A36,stroke:#2DD4BF,color:#F0FDFA
    style C fill:#134E4A,stroke:#5EEAD4,color:#F0FDFA
    style D fill:#102A36,stroke:#2DD4BF,color:#F0FDFA
    style E fill:#102A36,stroke:#2DD4BF,color:#F0FDFA
    style F fill:#102A36,stroke:#2DD4BF,color:#F0FDFA
```

The learning logic is simple: forgotten words return sooner, while successfully recalled words receive longer review intervals.

---

## 04 — Engineering Mindset

**How I approach building software**

| Principle | Approach |
|:---|:---|
| Problem First | Understand the actual user problem before choosing a technology. |
| Systems Thinking | Think about data flow, integrations, maintainability, and architecture. |
| AI as a Tool | Use AI assistants to explore solutions, accelerate implementation, and learn. |
| Iterative Development | Build, test, identify weaknesses, and improve. |
| User-Centred Design | Prioritize accessibility, clarity, and practical value. |

I use AI-assisted development tools such as ChatGPT, Gemini, Claude, and Qwen as collaborators in research, debugging, prototyping, and development.

---

## 05 — Technology

*Tools and technologies I work with and continue to explore.*

**Frontend & Application Development**

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,react,nextjs,tailwind,pwa" alt="Frontend technologies" />
</p>

**Backend & Database**

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb" alt="Backend technologies" />
</p>

**AI & Integrations**

<p>
  <img src="https://skillicons.dev/icons?i=openai,googleai,postman" alt="AI and API tools" />
</p>

**Development Tools & Platforms**

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,vercel" alt="Development tools" />
</p>

---

## 06 — GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats-fast.vercel.app/api?username=Talha0708&show_icons=true&theme=transparent&hide_border=true&title_color=2DD4BF&icon_color=2DD4BF&text_color=94A3B8&rank_icon=github" alt="GitHub statistics" />

<img height="165" src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=Talha0708&layout=compact&langs_count=6&theme=transparent&hide_border=true&title_color=2DD4BF&text_color=94A3B8" alt="Most used programming languages" />

<br>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=Talha0708&bg_color=00000000&color=94A3B8&line=2DD4BF&point=5EEAD4&area=true&hide_border=true" alt="GitHub contribution activity" />

</div>

---

## 07 — Beyond the Code

I believe good engineering is not only about writing code. It is also about identifying meaningful problems, learning continuously, and building solutions that people can actually use.

Currently interested in collaborating on:

- AI-powered applications and automation.
- Full-stack web applications.
- Educational technology and learning platforms.
- Open-source projects and innovative product ideas.

---

## 08 — Let's Connect

**Have an interesting idea, a technical challenge, or a project worth building?**

I'm open to meaningful conversations, collaboration, and opportunities to learn and contribute.

<div align="center">

<a href="mailto:talhabelal62@gmail.com">
  <img src="https://img.shields.io/badge/LET'S_TALK-0F766E?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Talha" />
</a>
<a href="https://linkedin.com/in/talha-belal-6a52371b6/">
  <img src="https://img.shields.io/badge/CONNECT_ON_LINKEDIN-102A36?style=for-the-badge&logo=linkedin&logoColor=67E8D2" alt="Connect on LinkedIn" />
</a>

<br><br>

**Talha Belal**  
*Computer Science & Engineering · Primeasia University*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F766E,50:102A36,100:07111F&height=110&section=footer" width="100%" alt="" />

</div>
