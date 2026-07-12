<h1 align="center">🍀 MinKyu Kang</h1>

<p align="center">
<b>Building Intelligent Systems from Data to Deployment</b><br>
AI • Data Engineering • Digital Twin • Scientific Computing
</p>

<p align="center">
  <a href="https://www.notion.so/s-Story-71fc24d2ac054f36a041997cea449904">
    <img src="https://img.shields.io/badge/Portfolio-Notion-black?style=for-the-badge&logo=notion&logoColor=white"/>
  </a>

  <a href="https://www.linkedin.com/in/minkyu484b84286">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>

  <a href="mailto:gangmingyu76@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

# 👋 About Me

I am an AI/Data Engineer passionate about designing end-to-end intelligent systems that connect **data engineering, machine learning, simulation, and software engineering**.

Rather than focusing solely on model performance, I enjoy building complete AI services—from data collection and preprocessing to deployment and user-facing applications.

My recent work spans **Digital Twin**, **Large Language Models (LLMs)**, **Retrieval-Augmented Generation (RAG)**, **Scientific Computing**, **NLP**, and **Research Data Management**, with a strong emphasis on translating complex problems into scalable, production-ready systems.

---

# 🚀 Career Snapshot

- 🎓 **B.S. in Data Science & Software**, Sungkyunkwan University *(Expected Aug. 2026)*
- 🏢 Incoming **Digital Twin Engineer**, GS Engineering & Construction (Plant Division)
- 📑 International Conference Paper submitted to **ICSOC 2026**
- ©️ Registered Software: **CEVSim** (Korea Copyright Commission)
- 🏆 Multiple awards in AI, Data Science, Smart Manufacturing, and Public Data Competitions
- 📚 Research Assistant for National Research Data Management (KRM)
- 🌎 Participant, University of Washington Global Data Science Program

---
# 🎓 Education

| Period | Institution | Major |
|----------|------------|--------|
| 2019 – 2026 | Sungkyunkwan University | B.S. in Data Science (Major) |
| 2024 – 2026 | Sungkyunkwan University | B.S. in Software (Double Major) |

**GPA**

| Category | GPA |
|-----------|------:|
| Overall | **4.03 / 4.5** |
| Major (Data Science) | **4.13 / 4.5** |

---
# 💼 Experience

| Period | Organization | Position | Description |
|---------|--------------|----------|-------------|
| Jul. 2026 – Present | GS Engineering & Construction | Digital Twin Engineer | Plant Division · Digital Twin Team |
| Sep. 2024 – Dec. 2025 | SKKU Institute of Information Management | Research Assistant | National Research Data Management (KRM DB Construction) |
| Sep. 2024 – Dec. 2024 | DXLab | Undergraduate Researcher | Multimodal Harmful Content Filtering |
| Mar. 2023 – Aug. 2024 | DScover | President | Data Science Academic Society |
| Jan. 2024 | University of Washington | Global Data Science Program | Winter Exchange Program |
| Mar. 2024 – Nov. 2024 | K-Software Empowerment Bootcamp | Team Leader | AI/Data Engineering Program |

---
# ⭐ Featured Projects

| Project | Domain | Tech Stack | Highlights |
|----------|---------|------------|------------|
| 🏭 **CEVSim** | Digital Twin | Three.js · PBM · Scientific Computing | ICSOC 2026 · Software Registration |
| 🎫 **Safe Ticket** | Explainable AI | RAG · FastAPI · PostgreSQL · Chrome Extension | Real-time Fraud Detection |
| 🏛 **Youth Policy RAG** | LLM Application | MySQL · FAISS · GPT · Node.js | Personalized Recommendation |
| 📚 **KRM Subject Classification** | NLP | RoBERTa · ML · Metadata Engineering | KSIM 2024 Presentation |
| 🧠 **Mental Health AI** | NLP | BERT · CURE · SNGP | Real-time Mental Health Detection |
| 🍽 **Meal Support Hub Optimization** | GIS | QGIS · MCLP · Spatial Analysis | National Chairman's Award |
| 🌃 **Coolness Night Map** | Tourism Analytics | Public Data · Visualization | Korea Tourism Contest |

---
---

# 🚀 Flagship Projects

## 🏭 CEVSim
### Population Balance Model-based Digital Twin for Cosmetic Manufacturing

> **A web-based digital twin simulator for cosmetic emulsification processes integrating Population Balance Modeling (PBM), Scientific Computing, and 3D visualization.**

### Highlights

- 🧪 Developed a **65-node Fixed-Pivot Population Balance Model (PBM)** to simulate droplet size evolution during emulsification.
- 🏭 Built a **Three.js-based Digital Twin** capable of visualizing the internal mixing process of cosmetic manufacturing vessels.
- 📈 Predicted four critical quality indicators:
  - D₃₂ (Mean Droplet Size)
  - H-Index (Uniformity)
  - Viscosity
  - Hardness
- ⚙️ Implemented **Equal-Energy-Dissipation Scale-Up** logic for **100L / 300L / 500L** production vessels.
- ✅ Designed an automated quality evaluation system using **PASS / REVIEW / FAIL** criteria.
- 🏢 Validated simulation outputs against **real industrial manufacturing batches**.

### Research & Achievement

- 📄 International Conference Paper submitted to **ICSOC 2026**
- ©️ Registered Software at the **Korea Copyright Commission**
- 🌐 Web-based Digital Twin Simulator (GitHub Pages)

### Tech Stack

`Three.js` `PBM` `Scientific Computing` `Numerical Analysis`
`Digital Twin` `JavaScript` `Physics Engine`

---

## 🎫 Safe Ticket
### Explainable AI Platform for Used Ticket Fraud Detection

> **An end-to-end AI system combining RAG, Chrome Extension, and Explainable AI to detect fraud in second-hand ticket transactions.**

### Highlights

- 🔍 Built a **Fraud Memory** using PostgreSQL + pgvector.
- 🤖 Designed a **multi-stage RAG pipeline**:
  - Data Collection
  - Entity Extraction
  - Embedding
  - Retrieval
  - LLM Analysis
  - Risk Scoring
- 🧠 Implemented **Explainable AI** capable of highlighting suspicious conversations.
- 🌐 Developed a **Chrome Extension** enabling real-time fraud analysis.
- 🚀 Integrated external verification services including **TheCheat** and police fraud databases.
- 📊 Built an asynchronous FastAPI-based scan pipeline with polling architecture.

### My Contribution

- Built the complete **data engineering pipeline**
- Designed the **Fraud Memory**
- Developed the **Entity Extraction Pipeline**
- Managed PostgreSQL database construction

### Tech Stack

`FastAPI`
`PostgreSQL`
`pgvector`
`Gemini`
`RAG`
`Docker`
`AWS`
`Playwright`

---

## 🏛 Youth Policy RAG
### Personalized Policy Recommendation Platform

> **A Retrieval-Augmented Generation platform that combines structured filtering and semantic retrieval to recommend personalized youth policies.**

### Highlights

- Designed a **Hybrid Retrieval Architecture**
  - SQL Hard Filtering
  - FAISS Vector Search
  - LLM Re-ranking
- Reduced hallucination by validating policy eligibility before LLM generation.
- Built an end-to-end recommendation workflow:
  - User Profiling
  - Recommendation
  - Search
  - Bookmark
  - Review
- Authored Software Requirement Specification (SRS) and Software Design Document (SDD).

### My Contribution

- Requirement Engineering
- Software Architecture Design
- Test Scenario Design
- Acceptance Criteria Definition

### Tech Stack

`MySQL`
`FAISS`
`GPT`
`Node.js`
`React`
`Software Engineering`

---

## 📚 Metadata-Based Subject Classification

> **Automatic subject classification for national research data repositories using metadata engineering and transformer-based NLP models.**

### Highlights

- Processed **12,120 research records**
- Redesigned taxonomy
  - **45 → 35 classes**
- Built metadata integration pipeline
- Compared
  - SVM
  - Random Forest
  - XGBoost
  - RoBERTa
- Achieved

Accuracy **79.2%**

F1-score **77.5%**

### Achievement

📄 Presented at

**KSIM 2024**

### Tech Stack

`Python`
`RoBERTa`
`Scikit-learn`
`Metadata Engineering`

---

## 🧠 Mental Health AI

> **Real-time mental health detection system using uncertainty-aware NLP models.**

### Highlights

- Processed **210,805 → 43,466** counseling sentences.
- Built symptom-aware NLP datasets.
- Combined
  - BERT
  - CURE
  - SNGP
- Designed an uncertainty-aware diagnosis framework.
- Developed a web-based mental health chatbot.

### Tech Stack

`BERT`
`PyTorch`
`NLP`
`Uncertainty Learning`

---
---

# 📑 Research & Publications

| Year | Type | Title | Status |
|------|------|-------|--------|
| 2026 | International Conference | **Population Balance Model-Based Cosmetic Emulsion Scale-Up Simulator** | Submitted to **ICSOC 2026 (Industry Track)** |
| 2026 | Software Registration | **CEVSim (Cosmetic Emulsification Vessel Scale-Up Simulator)** | Registered (Korea Copyright Commission) |
| 2024 | Domestic Conference | **Metadata-Based Automatic Subject Classification for Research Data Management Systems** | Presented at **KSIM 2024** |

---

# 🏆 Awards

| Year | Award | Project / Achievement |
|------|-------|------------------------|
| 2025 | 🥇 Chairman's Award | Meal Support Hub Optimization (National Happiness Service Discovery Competition) |
| 2025 | 🥉 Encouragement Prize | Seoul Coolness Night Tourism Map (Korea Tourism Data Contest) |
| 2024 | 🥈 ICT Solution Award | Min-Max-Median Priority Queue |
| 2024 | 🥈 Hackathon Award | Flood Vulnerability Analysis |
| 2024 | 🥇 Grand Prize | Public Waste Bin Location Optimization |
| 2024 | 🏅 Best Academic Society | DScover President |
| 2023 | 🥈 Academic Conference Silver Prize | Hate Speech Classification |

---

# 📜 Certifications

| Certificate | Issued |
|--------------|--------|
| SQL Developer (SQLD) | 2024 |
| Advanced Data Analytics Semi-Professional (ADsP) | 2023 |
| Computer Specialist Level 2 | 2020 |
| Korean History Proficiency Test Level 1 | 2019 |
| Driver's License (Class 2) | 2020 |

---

# 🛠 Tech Stack

## Languages

<p>
<img src="https://skillicons.dev/icons?i=python,java,js,ts,sql,r" />
</p>

---

## AI / Machine Learning

<p>

<img src="https://img.shields.io/badge/Pytorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>

<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>

<img src="https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge"/>

<img src="https://img.shields.io/badge/LangChain-121212?style=for-the-badge"/>

<img src="https://img.shields.io/badge/RAG-4B5563?style=for-the-badge"/>

<img src="https://img.shields.io/badge/LLM-111827?style=for-the-badge"/>

</p>

---

## Data Engineering

<p>

<img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,docker,git,github"/>

<img src="https://img.shields.io/badge/FAISS-2563EB?style=for-the-badge"/>

<img src="https://img.shields.io/badge/pgvector-0F766E?style=for-the-badge"/>

<img src="https://img.shields.io/badge/ETL-374151?style=for-the-badge"/>

</p>

---

## Backend

<p>

<img src="https://skillicons.dev/icons?i=fastapi,nodejs,react,nextjs"/>

</p>

---

## Scientific Computing

<p>

<img src="https://img.shields.io/badge/Digital Twin-2563EB?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Population Balance Model-4F46E5?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js"/>

<img src="https://img.shields.io/badge/Scientific Computing-1D4ED8?style=for-the-badge"/>

</p>

---

# 📊 GitHub Analytics

<p align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=mingu0215&show_icons=true&count_private=true"/>

<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mingu0215&layout=compact"/>

</p>

<p align="center">

<img src="https://streak-stats.demolab.com?user=mingu0215"/>

</p>

---

# 🎯 Current Focus

```text
Digital Twin
        │
Scientific Computing
        │
AI Engineering
        │
Data Engineering
        │
Large Language Models
        │
Retrieval-Augmented Generation
        │
Research Data Systems
