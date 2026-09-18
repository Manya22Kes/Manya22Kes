<div align="center">
  <img src="./header.svg" width="100%" alt="Manya Keserwani Header" />
</div>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1000&color=60A5FA&center=true&vCenter=true&width=700&lines=Building+Real-Time+AI+%26+Full-Stack+Platforms;Architecting+Microservices+%7C+FastAPI+%2B+Node.js+%2B+React;Computer+Vision+%7C+Custom+YOLOv8+(91.44%25+Precision);Real-Time+Pipelines+with+WebSockets+%26+Event+Streaming;Passionate+about+DAA%2C+OOPS%2C+DBMS+%26+System+Design;200%2B+DSA+Problems+Solved+on+LeetCode" alt="Typing SVG" />
  </a>
</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Manya_Keserwani-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manya-keserwani-2b8686357)
[![Email](https://img.shields.io/badge/Email-manyaintelinfo.18%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:manyaintelinfo.18@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-200%2B_Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/Manya22Kes/)
[![GitHub](https://img.shields.io/badge/GitHub-Manya22Kes-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Manya22Kes)

</div>

---

# 💫 About Me

👋 Hey there! I'm **Manya** — a Full-Stack & AI/ML Engineer passionate about architecting scalable microservices, low-latency real-time pipelines, and production-grade computer vision systems.

🔭 **I'm currently working on:**  
**[VIGILANT](#-flagship-project-vigilant--autonomous-real-time-surveillance--alert-system)** — an enterprise-grade, real-time AI video surveillance and alert system that performs restricted-zone monitoring using a custom-trained **YOLOv8** model.

🤝 **I'm looking to collaborate on:**  
High-performance backend systems, real-time streaming architectures, AI/ML-driven developer tooling, and innovative open-source projects.

🧠 **Engineering Focus & Core Concepts:**  
- **Real-Time Systems & WebSockets:** Low-latency event streaming, bi-directional client-server synchronization, and live telemetry feeds.
- **DAA (Design & Analysis of Algorithms):** Algorithmic complexity, Point-in-Polygon geometric intersection, sliding-window temporal tracking, and rate-limiting / throttling algorithms.
- **OOPS (Object-Oriented Programming):** SOLID principles, modular service encapsulation, clean API contracts, and model-agnostic abstraction layers.
- **DBMS & Data Persistence:** Relational schema design (**PostgreSQL**), vector embeddings & similarity search (**`pgvector`**), document stores (**MongoDB**), and distributed caching/message queues (**Redis**).
- **AI / ML & Computer Vision:** Custom deep learning architectures (**YOLOv8**), transfer learning, model evaluation metrics, and multi-modal LLM integration.
- **Cloud Computing & DevOps:** Containerized microservices (**Docker, Docker Compose**), **Nginx** reverse proxies, cloud infrastructure (**AWS, GCP, Railway, Render, Vercel, Netlify**), and **CI/CD via GitHub Actions**.
- **Data Analytics:** Real-time spatial analytics, intrusion dwell-time metrics, confidence score distributions, and temporal trend tracking.

🌱 **I'm currently exploring:**  
Retrieval-Augmented Generation (RAG), Agentic AI Workflows & Multi-Agent Orchestration, Vector Search Optimization, and Fine-Tuning Open-Source LLMs.

💬 **Ask me about:**  
Real-time pipelines, **YOLOv8** computer vision, Python/FastAPI microservices, Node.js/Express, React/TypeScript, WebSockets, and database architecture.

⚡ **Fun fact:**  
I enjoy turning *"it works"* into interactive 3D visual experiences backed by sub-second latency and mathematical reliability.

---

# 🛡️ Flagship Project: VIGILANT — Autonomous Real-Time Surveillance & Alert System

> **An AI-based real-time video surveillance and restricted-zone monitoring engine powered by custom-trained YOLOv8 and event-driven microservices.**

<div align="center">

![System](https://img.shields.io/badge/System-Real--Time_Surveillance-0284C7?style=flat-square&logo=shield)
![Model](https://img.shields.io/badge/YOLOv8-91.44%25_Precision-10B981?style=flat-square&logo=opencv)
![Architecture](https://img.shields.io/badge/Architecture-3--Tier_Microservices-8B5CF6?style=flat-square&logo=fastapi)
![Streaming](https://img.shields.io/badge/WebSockets-Real--Time_Streaming-F59E0B?style=flat-square&logo=socketdotio)
![3D UI](https://img.shields.io/badge/Frontend-React_Three_Fiber_(3D)-EC4899?style=flat-square&logo=threedotjs)
![Security](https://img.shields.io/badge/Security-JWT_%26_bcrypt-EF4444?style=flat-square&logo=jsonwebtokens)

</div>

### 🔑 Key Architectural & Engineering Highlights:

1. **Decoupled 3-Service Microservice Architecture:**  
   Architected a three-tier full-stack system consisting of a **Python/FastAPI ML microservice**, a **Node.js/Express backend**, and a **React/TypeScript frontend**. Cleanly isolated the trained YOLOv8 model behind a lightweight, high-performance API so ML inference workloads and product layers build, scale, and deploy independently.

2. **End-to-End Real-Time Pipeline & WebSockets (91.44% Precision):**  
   Engineered a seamless sub-second detection pipeline:  
   $$\text{Camera Capture} \longrightarrow \text{Model Inference} \longrightarrow \text{Zone-Containment Verification} \longrightarrow \text{Severity Scoring} \longrightarrow \text{Instant WebSocket Broadcast}$$  
   Integrated a custom-trained **YOLOv8** model that achieved **91.44% precision** on held-out test data for restricted-zone detection.

3. **Interactive, Resolution-Independent Polygon Zone Editor:**  
   Designed a dynamic vector boundary editor where users click to place vertices and drag to reposition zone boundaries directly over a live video feed. Boundary coordinates are stored as **normalized coordinates** ($x, y \in [0, 1]$) rather than fixed pixel dimensions — eliminating the brittle hardcoded-rectangle limitation and ensuring precision across any resolution or display aspect ratio.

4. **Dwell-Time-Aware Severity & Cooldown Throttling Algorithm:**  
   Designed a temporal scoring algorithm that evaluates threat severity by model detection confidence, live occupancy count, and continuous cross-frame dwell duration in the restricted area. Incorporated sliding-window cooldown throttling to prevent duplicate alerts and notification storms.

5. **Interactive 3D Landing Experience & Hardened Security:**  
   Built an engaging 3D landing environment with **React Three Fiber (Three.js)**, paired with **JWT and bcrypt** authentication protecting configuration endpoints and monitoring controls — combining real-time systems, 3D graphics, and security fundamentals in one project.

---

# 🚀 Other Featured Projects

<details open>
<summary><b>🤖 RepoPilot AI — AI-Powered GitHub Automation Agent</b></summary>
<br>

- Full-stack AI automation platform leveraging the **GitHub Apps API** to auto-triage issues, summarize pull requests, and detect duplicate tickets via semantic vector search (**PostgreSQL + `pgvector`**).
- Designed a model-agnostic LLM abstraction layer (**Gemini + OpenAI**) with automatic failover and rule-based fallback.
- Architected an asynchronous job-processing queue (**Node.js, Express, BullMQ, Redis**) to decouple webhook ingestion from AI processing with idempotency guarantees.
- Containerized with **Docker Compose** and deployed on **Railway**.
</details>

<details open>
<summary><b>🔍 Prism — AI-Powered Misinformation & Credibility Analyzer</b></summary>
<br>

- Multi-modal AI credibility platform ingesting **7 content formats** (text, URLs, PDFs, DOCX, PPTX, images, audio), leveraging the **Gemini API** for real-time fact-checking.
- Built a dual-layer OCR and speech-to-text pipeline (**Google Cloud Vision API, Tesseract.js fallback, Google Cloud Speech-to-Text**) for robust document and audio extraction.
- Containerized with **Docker Compose** and an **Nginx** reverse proxy; features an interactive **Three.js / React Three Fiber** 3D interface.
</details>

<details>
<summary><b>🔐 Authify — Production-Grade Authentication Engine</b></summary>
<br>

- End-to-end authentication platform built with **React + Vite, Context API, Node.js/Express, and MongoDB**.
- Implemented **JWT refresh-token rotation**, Axios interceptor request queuing, role-based access control (RBAC), and Google OAuth integration.
</details>

---

# 💻 Tech Stack & Tooling

<div align="center">

### 🗣️ Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

### 🤖 AI, Machine Learning & Computer Vision
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit--Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)

### ⚙️ Backend, Real-Time & Systems
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-CC292B?style=for-the-badge&logo=redis&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-005571?style=for-the-badge&logo=postman&logoColor=white)

### 🎨 Frontend, 3D & Creative Tech
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)
![React Three Fiber](https://img.shields.io/badge/React_Three_Fiber-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### 🗄️ Databases & Storage
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

### ☁️ Cloud, DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

</div>

---

# 📊 GitHub Analytics & Live Stats

<div align="center">

<img src="https://github-readme-stats.shion.dev/api?username=Manya22Kes&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" height="175" />
<img src="https://streak-stats.demolab.com/?user=Manya22Kes&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="175" />

<br/><br/>

<img src="https://github-readme-stats.shion.dev/api/top-langs/?username=Manya22Kes&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="160" />

<br/><br/>

### ✍️ Random Dev Quote
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Dev Quote" />

</div>

---

<div align="center">

[![Visitors](https://komarev.com/ghpvc/?username=Manya22Kes&label=Profile%20Views&color=2563EB&style=flat-square)](https://github.com/Manya22Kes)

*“Turning 'it works' into interactive 3D experiences with sub-second latency and mathematical reliability.”*

</div>
