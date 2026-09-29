<!--
  Rajiv Jha — GitHub Profile README
  Focus:
  Software Engineering • Machine Learning • DSA • Real-World Systems
-->

<div align="center">

<a href="https://github.com/jharajiv315">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:1e293b&height=190&section=header&text=RAJIV%20JHA&fontSize=46&fontColor=ffffff&fontAlignY=35&desc=Computer%20Science%20Student%20%C2%B7%20Aspiring%20AI%2FML%20Engineer&descAlignY=59&descSize=17&animation=fadeIn"
    width="100%"
    alt="Rajiv Jha — Computer Science Student and Aspiring AI/ML Engineer"
  />
</a>

<br />

<a href="https://github.com/jharajiv315">
  <img
    src="https://img.shields.io/badge/GitHub-0f172a?style=for-the-badge&logo=github&logoColor=white"
    alt="GitHub"
  />
</a>

<a href="https://www.linkedin.com/in/rajiv-jha-9b36ba3a2/">
  <img
    src="https://img.shields.io/badge/LinkedIn-0f172a?style=for-the-badge&logo=linkedin&logoColor=white"
    alt="LinkedIn"
  />
</a>

<a href="https://leetcode.com/u/Rajiv_Jha/">
  <img
    src="https://img.shields.io/badge/LeetCode-0f172a?style=for-the-badge&logo=leetcode&logoColor=white"
    alt="LeetCode"
  />
</a>

<a href="https://portfolio-beta-ochre-90.vercel.app/">
  <img
    src="https://img.shields.io/badge/Portfolio-0f172a?style=for-the-badge&logo=vercel&logoColor=white"
    alt="Portfolio"
  />
</a>

<br /><br />

<img
  src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=16&duration=2800&pause=1200&color=94A3B8&center=true&vCenter=true&width=760&lines=Building+full-stack+systems;Learning+machine+learning+from+first+principles;Solving+problems+with+DSA+in+Java;Turning+ideas+into+real+software"
  alt="Rajiv Jha profile focus"
/>

</div>

---

## `01` — About

I'm **Rajiv Jha**, a **B.Tech Computer Science student** graduating in **2029**, focused on becoming an **AI/ML Engineer**.

My interests sit at the intersection of:

**Software Engineering · Algorithms · Data · Machine Learning · Product Development**

I learn by building real systems, understanding the fundamentals behind them, debugging what breaks, and improving the implementation over time.

I'm especially interested in the complete path from a technical problem to a usable system:

```text
Problem
   ↓
Data
   ↓
Model
   ↓
Backend
   ↓
API
   ↓
Product
   ↓
Deployment
```

My goal is not only to build models, but to understand the engineering required to turn models and algorithms into reliable software systems.

---

## `02` — Current Focus

| Area | Focus |
|---|---|
| 🧠 DSA | Graphs · Backtracking · Dynamic Programming |
| 🤖 Machine Learning | EDA · Feature Engineering · Preprocessing · Model Building · Evaluation |
| ⚙️ Backend | Python · Node.js · Express · REST APIs |
| 🌐 Full Stack | React · JavaScript · MERN |
| 🗄️ Data | PostgreSQL · SQL · NumPy · Pandas |
| 🛠️ Engineering | Git · GitHub · APIs · Testing · Deployment |

---

## `03` — Tech Stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=java,python,javascript,c,cpp&perline=10" alt="Java Python JavaScript C C++" />
</p>

### Frontend & Application Development

<p>
  <img src="https://skillicons.dev/icons?i=react,nodejs,express,vite,tailwind&perline=10" alt="React Node.js Express Vite Tailwind CSS" />
</p>

### Data & Machine Learning

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="45" alt="Python" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="45" alt="NumPy" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" height="45" alt="Pandas" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" height="45" alt="Matplotlib" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" height="45" alt="Scikit-learn" />
</p>

### Databases & Tools

<p>
  <img src="https://skillicons.dev/icons?i=postgresql,mongodb,git,github,vscode,figma&perline=10" alt="PostgreSQL MongoDB Git GitHub VS Code Figma" />
</p>

> I prefer listing technologies after I've actually used them in code or projects.

---

# `04` — Selected Projects

## 🟢 KRIVIO AI

**AI-assisted digital business mentor and commerce acceleration platform for rural Indian artisans, weavers, farmers, and Self-Help Groups.**

KRIVIO is designed around practical digital-commerce challenges such as product presentation, catalog creation, vernacular interaction, marketplace readiness, and access to business resources.

### Highlights

- Voice-first business assistance across **7 Indian languages**
- Multimodal AI workflows for product understanding and creative generation
- Product identity extraction from product imagery
- Marketplace-ready catalog generation and export workflows
- Public digital storefronts for direct customer interaction
- PostgreSQL-backed application data and user workflows
- React + TypeScript + Vite frontend
- FastAPI/Python services
- Gemini-powered multimodal capabilities
- Supabase-based authentication and user synchronization

### Architecture

```text
Artisan Voice / Image
        ↓
KRIVIO Client
        ↓
Authenticated Application Gateway
        ↓
Contextual Business Engine
        ├──────────────→ Gemini Multimodal AI
        ├──────────────→ PostgreSQL
        └──────────────→ Marketplace / Storefront Workflows
```

### Stack

`React` `TypeScript` `Vite` `FastAPI` `Python` `PostgreSQL` `Gemini` `Supabase`

**Repository:**  
https://github.com/jharajiv315/KRIVIO-AI

---

## 🟤 Portfolio & Headless CMS

**A full-stack portfolio platform with a public frontend, administrator dashboard, REST API, and PostgreSQL persistence.**

Instead of maintaining portfolio content directly inside frontend source files, the platform uses a headless CMS architecture where projects, skills, timeline entries, profile information, media, and visitor messages can be managed through the admin dashboard.

### Architecture

```text
                         ┌─────────────────────┐
                         │    Public Visitor   │
                         └──────────┬──────────┘
                                    ↓
                         ┌─────────────────────┐
                         │ React + Vite        │
                         │ Public Portfolio    │
                         └──────────┬──────────┘
                                    ↓
                         ┌─────────────────────┐
                         │ Express REST API    │
                         └───────┬─────┬───────┘
                                 ↓     ↓
                          PostgreSQL  Cloudinary
                                 │
                                 ↓
                            SMTP / Email


                         ┌─────────────────────┐
                         │     Administrator   │
                         └──────────┬──────────┘
                                    ↓
                         ┌─────────────────────┐
                         │ React + Redux       │
                         │ Admin Dashboard     │
                         └──────────┬──────────┘
                                    ↓
                              Express API
```

### Engineering Highlights

- Decoupled public portfolio frontend and admin dashboard
- Express + PostgreSQL REST API
- JWT authentication using HTTP-only cookies
- Protected administrative CRUD operations
- Dynamic project, skill, timeline, and profile management
- Cloudinary-backed media workflows
- Contact-message persistence and management
- React/Vite + Tailwind + Framer Motion frontend
- Redux Toolkit + Radix UI dashboard
- Automated CI, linting, backend testing, and production build validation

### Stack

`React` `Vite` `Tailwind CSS` `Framer Motion` `Node.js` `Express` `PostgreSQL` `JWT` `Cloudinary` `Redux Toolkit`

**Live:**  
https://portfolio-beta-ochre-90.vercel.app/

**Repository:**  
https://github.com/jharajiv315/Portfolio

---

## 🔵 TRUVA

**AI-Assisted Legal Metrology & Packaged Commodity Inspection Platform**

TRUVA is an AI-assisted inspection platform designed to automate verification of mandatory statutory declarations on packaged commodities under the **Legal Metrology (Packaged Commodities) Rules, 2011**.

The system combines OCR, spatial document intelligence, deterministic extraction, evidence arbitration, and rule-based compliance evaluation.

### My Contribution

**Machine Learning · Backend**

### Engineering Highlights

- PaddleOCR PP-OCRv4 for text detection and recognition
- Fine-tuned LayoutLMv3 for token-level key information extraction
- 37 BIO entity classes for statutory declarations
- Deterministic extraction for addresses, MRP, net quantity, and dates
- Evidence arbitration between ML predictions and deterministic extraction
- Evidence firewall requiring traceable OCR bounding boxes
- Rule-based compliance evaluation
- FastAPI REST backend
- SQLite-based inspection persistence
- Interactive bounding-box inspection interface
- Canonical JSON response schema
- Automated unit, adversarial, and end-to-end tests

### ML Pipeline

```text
Packaging Image
      ↓
PaddleOCR
      ↓
OCR Tokens + Bounding Boxes
      ↓
LayoutLMv3
      ↓
Entity Candidates
      ↓
Deterministic Statutory Extraction
      ↓
Evidence Arbitration
      ↓
Legal Metrology Rule Engine
      ↓
Canonical Compliance Result
```

### Reported Results

- **89.4% Entity F1-Score** on the documented holdout statutory-declaration test set
- **94.2% Token Accuracy**
- Approximately **1.8–2.8 seconds end-to-end per SKU** on the documented Intel Core i5 / 16 GB RAM / CPU-only benchmark environment

### Stack

`Python` `FastAPI` `React` `TypeScript` `PaddleOCR` `LayoutLMv3` `PyTorch` `SQLite`

**Repository:**  
https://github.com/jharajiv315/TRUVA

---

## 🟣 ChitraSathi / MindSpace

**Digital Mental Health Support Platform for Students**

ChitraSathi / MindSpace is a student-focused mental-health platform built around accessible digital support, mood tracking, AI-assisted interaction, resources, and professional-support workflows.

### Highlights

- AI-powered conversational support
- Camera-based mood and emotion analysis
- Historical mood tracking and analytics
- Personalized resource recommendations
- Multi-format resource library
- Counselor booking workflows
- Peer-support concepts
- Crisis-support workflows
- Anonymous interaction options
- Responsive and mobile-oriented application design

### AI / ML

- TensorFlow.js-based client-side mood analysis
- Python-based ML services
- TensorFlow
- OpenCV
- Facial-expression recognition
- Google AI APIs for natural-language interaction

### Stack

`HTML` `CSS` `JavaScript` `Node.js` `Express.js` `MongoDB` `JWT` `Socket.io` `Python` `TensorFlow` `OpenCV` `TensorFlow.js`

**Repository:**  
https://github.com/jharajiv315/ChitraSathi

---

# `05` — Problem Solving

I use **Java and DSA** as a foundation for algorithmic thinking.

My approach:

```text
Understand the problem
        ↓
Build a brute-force solution
        ↓
Analyze time & space complexity
        ↓
Identify the bottleneck
        ↓
Optimize
        ↓
Implement
        ↓
Test edge cases
```

Core areas include:

```text
Arrays
Linked Lists
Stacks
Queues
Hashing
Sorting
Trees
Graphs
Backtracking
Dynamic Programming
```

---

# `06` — GitHub Activity

<div align="center">

<a href="https://github.com/jharajiv315">
  <img
    height="180"
    src="https://github-readme-stats.vercel.app/api?username=jharajiv315&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0f172a&title_color=f8fafc&text_color=cbd5e1&icon_color=94a3b8&rank_icon=github"
    alt="Rajiv Jha GitHub statistics"
  />
</a>

<a href="https://github.com/jharajiv315">
  <img
    height="180"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=jharajiv315&layout=compact&langs_count=8&hide_border=true&bg_color=0f172a&title_color=f8fafc&text_color=cbd5e1"
    alt="Rajiv Jha most used programming languages"
  />
</a>

</div>

<br />

<div align="center">

<a href="https://github.com/jharajiv315">

<img
  src="https://streak-stats.demolab.com?user=jharajiv315&theme=dark&hide_border=true&background=0F172A&ring=94A3B8&fire=FFFFFF&currStreakLabel=F8FAFC&sideLabels=CBD5E1&dates=94A3B8"
  alt="Rajiv Jha GitHub contribution streak"
/>

</a>

</div>

---

# `07` — LeetCode

<div align="center">

<a href="https://leetcode.com/u/Rajiv_Jha/">

<img
  src="https://leetcard.jacoblin.cool/Rajiv_Jha?theme=dark&ext=activity"
  alt="Rajiv Jha LeetCode statistics"
/>

</a>

<br /><br />

<a href="https://leetcode.com/u/Rajiv_Jha/">

<img
  src="https://img.shields.io/badge/LeetCode-@Rajiv__Jha-0f172a?style=for-the-badge&logo=leetcode&logoColor=white"
  alt="Rajiv Jha LeetCode profile"
/>

</a>

</div>

---

# `08` — Engineering Journey

```text
2025
├── Programming fundamentals
├── Java
├── DSA foundations
├── Web development
└── Git / GitHub

2026
├── Advanced DSA
├── Python
├── NumPy
├── Pandas
├── PostgreSQL / SQL
├── Machine Learning
├── Full-Stack Development
└── Backend Engineering

Next
├── Deep Learning
├── PyTorch
├── MLOps
├── System Design
└── Production AI Systems
```

The long-term direction:

```text
Strong Foundations
        ↓
Strong Software Engineering
        ↓
Strong ML Fundamentals
        ↓
Reliable AI Systems
```

---

# `09` — Achievements

- **2× Hackathon Finalist**
- Built projects spanning software engineering, machine learning, backend systems, databases, and product development
- Worked across frontend, backend, APIs, database systems, and ML pipelines through individual and team projects

---

# `10` — What I Care About

```text
Understand > copy

Build > collect tutorials

Fundamentals > shortcuts

Consistency > intensity

Real projects > inflated skill lists

Measure > assume

Debug > hide problems

Clean systems > unnecessary complexity
```

---

# `11` — Engineering Philosophy

I don't want to learn technologies only as isolated tools.

I'm interested in how different engineering layers connect:

```text
Algorithms
     +
Data
     +
Machine Learning
     +
Backend
     +
APIs
     +
Frontend
     +
Deployment
```

The long-term goal is to build systems where these layers work together instead of treating them as separate technologies.

---

# `12` — Building Toward AI/ML Engineering

```text
Programming
     ↓
Data Structures & Algorithms
     ↓
Data & Statistics
     ↓
Machine Learning
     ↓
Backend & APIs
     ↓
AI Systems
     ↓
Deployment & MLOps
```

I'm building these foundations step by step rather than trying to skip directly to the final layer.

---

# `13` — Connect

<div align="center">

<a href="https://portfolio-beta-ochre-90.vercel.app/">
  <img
    src="https://img.shields.io/badge/Portfolio-View-0f172a?style=for-the-badge&logo=vercel&logoColor=white"
    alt="View portfolio"
  />
</a>

<a href="https://github.com/jharajiv315">
  <img
    src="https://img.shields.io/badge/GitHub-Follow-0f172a?style=for-the-badge&logo=github&logoColor=white"
    alt="Follow on GitHub"
  />
</a>

<a href="https://www.linkedin.com/in/rajiv-jha-9b36ba3a2/">
  <img
    src="https://img.shields.io/badge/LinkedIn-Connect-0f172a?style=for-the-badge&logo=linkedin&logoColor=white"
    alt="Connect on LinkedIn"
  />
</a>

<a href="https://leetcode.com/u/Rajiv_Jha/">
  <img
    src="https://img.shields.io/badge/LeetCode-Profile-0f172a?style=for-the-badge&logo=leetcode&logoColor=white"
    alt="View LeetCode profile"
  />
</a>

<a href="mailto:jharajiv315@gmail.com">
  <img
    src="https://img.shields.io/badge/Email-Contact-0f172a?style=for-the-badge&logo=gmail&logoColor=white"
    alt="Contact Rajiv Jha"
  />
</a>

<br /><br />

### Building. Learning. Debugging. Improving.

<sub>© Rajiv Jha · Computer Science Student · Aspiring AI/ML Engineer</sub>

</div>
