<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A66C2,100:181717&height=220&section=header&text=Muzammil%20Khan&fontSize=56&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%7C%20LLM%20Systems%20%7C%20RAG%20%26%20Agents&descAlignY=60&descSize=20" width="100%" alt="Muzammil Khan banner" />

<a href="https://github.com/muzammil-kj">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=800&color=0A66C2&center=true&vCenter=true&width=760&lines=Building+AI+agents+that+know+when+to+ask+a+human;Turning+LLMs+into+production+systems;RAG+pipelines+%7C+FastAPI+%7C+Qdrant+%7C+Docker;1st+Place+%E2%80%94+DevSynt+Rise+Summer+Internship+2026" alt="Typing animation" />
</a>

<br/><br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit_Site-4A4A4A?style=for-the-badge&logo=vercel&logoColor=white)](https://3d-portfolio-omega-jet.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muzammil-khan-87b185267/)
[![Email](https://img.shields.io/badge/Email-Reach_Out-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:muzammilkhan.kj@gmail.com)
[![Guardloop](https://img.shields.io/badge/Live_Demo-Guardloop-F59E0B?style=for-the-badge)](https://guardloop-iota.vercel.app)

</div>

---

## About me

I'm an **AI Engineer** and Information Technology graduate from NUML, Islamabad. I build **LLM-powered applications**, **RAG pipelines** and **automation systems** that have to behave reliably in production. My focus is the part that's easy to skip: deciding when an AI system should act on its own, and when it should hand the decision to a person.

- 🔭 **Now:** building **[Guardloop](https://github.com/muzammil-kj/guardloop)**, an open-source guardrail and observability layer for AI agents (FastAPI, Supabase, Next.js, Gemini)
- 🧬 **Recently:** AI/LLM Engineer Intern at **CarbonRepro**, working on a multi-agent healthcare platform with RAG pipelines and vector search
- ⚙️ **Automation:** n8n workflows for email triage, social publishing and recruitment pipelines
- 🎯 **Open to:** AI Engineer, LLM Engineer and AI Automation roles
- 💬 **Ask me about:** RAG design, agent safety and human-in-the-loop systems, n8n
- 🥾 **Outside code:** hiking, trekking, and tech community meetups

<img src="https://komarev.com/ghpvc/?username=muzammil-kj&style=flat-square&color=0A66C2&label=PROFILE+VIEWS" alt="profile views" />

---

## Tech stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,typescript,nextjs,react,tailwind,postgres,supabase,prisma,docker,git,github,linux,pandas,numpy,opencv,postman,vscode,mongodb,firebase,cpp,java,html,css" alt="Tech stack icons" />

<br/><br/>

![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Cohere](https://img.shields.io/badge/Cohere-39594D?style=for-the-badge)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-Pipelines-7C3AED?style=for-the-badge)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Discord](https://img.shields.io/badge/Discord_Webhooks-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)

</div>

---

## Featured projects

### 🛡️ Guardloop: guardrails for AI agents
Open-source layer that sits between AI agents and the real world. Agents report each decision; Guardloop escalates uncertain ones to a human reviewer, caps daily spend, masks personal data, and keeps an audit trail.

`FastAPI` · `Supabase (Postgres, Auth, Realtime, RLS)` · `Next.js` · `Gemini (LLM judge)` · `GitHub Actions` · `Docker`

- Human-in-the-loop review queue with roles, owners and deadlines
- LLM judge that re-checks a sample of auto-approved decisions, hiding the agent's own confidence from it
- Idempotent ingestion, daily budget circuit breaker, and PII masking before storage
- Python SDK on PyPI, CI on every pull request, and a 219-test backend suite

[![Live demo](https://img.shields.io/badge/Live_Demo-guardloop--iota.vercel.app-F59E0B?style=for-the-badge)](https://guardloop-iota.vercel.app) [![Source](https://img.shields.io/badge/Source-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/muzammil-kj/guardloop)

---

### 🩺 LifeSync: AI-driven mental wellness platform
**Finalist, Skill-Verse Nexus 2025 (NUML R&SI)** · Final-year project

`Python` · `ReactJS` · `Node.js/Express` · `MongoDB/Firebase` · `NLP` · `OpenCV` · `Ethereum`

- NLP chatbot for mental health support, with real-time facial emotion detection to fill in mood tracking
- Sentiment analysis on journal entries, with weekly progress reports
- Ethereum testnet audit logging of user and system actions
- Time Capsule module with an NSFW content filter and steganography for sensitive files

[![View Code](https://img.shields.io/badge/View_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/muzammil-kj/LifesyncKhan)

---

### ❤️ Cardiovascular disease risk prediction
`Python` · `Pandas` · `NumPy` · `Scikit-learn` · `Matplotlib` · `Seaborn`

- Binary classifier on a 303-patient clinical dataset (13 features)
- Benchmarked KNN, Random Forest and Logistic Regression; tuned with `GridSearchCV`
- **82.8% cross-validated accuracy (7-fold)**, with precision 81%, recall 89%, F1 85%
- Feature analysis: `sex` and `thal` as negative predictors, `cp` (chest pain type) as the strongest positive predictor

[![View Code](https://img.shields.io/badge/View_Code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/muzammil-kj/cardio_project)

---

## Experience

### 🏆 AI Engineer Intern, DevSynt (Rise Summer Internship 2026)
**1st place, Cohort 1** · Jul 2026 – Sep 2026 · Remote/Hybrid

<details open>
<summary><b>Six applied AI projects (click to expand)</b></summary>

1. **AI email filtering:** Gmail, Gemini importance classification, Discord and Telegram alerts, auto-archiving of low-priority mail, with error handling and an audit log
2. **AutoGram Engine:** Google Drive, SHA-256 deduplication, Supabase storage, Gemini Vision captions, published to Instagram through the Graph API
3. **AI hiring pipeline:** email and Google Forms intake merged into one schema, LLM ATS scoring (Strong / Average / Weak), with a human making the final decision
4. **Data cleaning and enrichment:** 1,250-record Kaggle dataset, documented data issues, careful duplicate handling and derived fields, loaded to Supabase
5. **RAG document Q&A:** upload, chunking, embeddings, vector search, and cited answers with "not found" guardrails
6. **AI email triage and RAG assistant:** intent and priority classification, RAG answers for general questions, and escalation of sensitive messages to people

</details>

### 🧬 AI/LLM/SLM Engineer Intern, CarbonRepro
Remote · Jun 2026 – Sep 2026

- Delivered three patient-facing AI agents end to end on a multi-agent healthcare platform (FastAPI, Prisma, PostgreSQL, Next.js)
- Built RAG pipelines: document ingestion, embeddings, Qdrant retrieval and Cohere/Gemini generation, returning source-cited answers
- Designed database schemas and migrations, background jobs, and alerting for health monitoring
- Built dashboards with Recharts and Clerk authentication, working through Git feature branches and pull requests

### 🐍 Python Development Intern, CodeAlpha
Jul 2024 – Oct 2024 · Virtual

- Built Python applications and scripts for real-world programming problems, following professional coding standards

### 📊 Data Analytics Intern, Elevvo Pathways
Aug 2025 – Sep 2025 · Virtual

- Cleaned Kaggle and retail datasets with Pandas, ran exploratory analysis, and prepared Scikit-learn train/test pipelines

---

## Education and certifications

**Bachelor of Information Technology**, National University of Modern Languages (NUML), Islamabad
Feb 2022 – Jan 2026 · **CGPA 3.56 / 4.0**

- **Machine Learning, AI & Data Science**, eHunar (2025)
- **Data Analytics and Business Intelligence**, DigiSkills.pk
- **Artificial Intelligence using Python**, DigiSkills.pk (2026)
- **English:** IELTS 7.5

---

## GitHub stats

<div align="center">

<img height="180" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=muzammil-kj&show_icons=true&hide_border=true&theme=tokyonight" />
<img height="180" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=muzammil-kj&layout=compact&hide_border=true&theme=tokyonight" />

<br/>

<img alt="GitHub streak" src="https://streak-stats.demolab.com/?user=muzammil-kj&hide_border=true&theme=tokyonight" />

<br/>

<img alt="Contribution activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=muzammil-kj&theme=tokyo-night&hide_border=true" width="90%" />

</div>

---

## Let's connect

<div align="center">

[![Email](https://img.shields.io/badge/Email-muzammilkhan.kj%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:muzammilkhan.kj@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Muzammil_Khan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muzammil-khan-87b185267/)
[![Portfolio](https://img.shields.io/badge/Portfolio-3D_Site-4A4A4A?style=for-the-badge&logo=vercel&logoColor=white)](https://3d-portfolio-omega-jet.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-muzammil--kj-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/muzammil-kj)

<br/>

<i>Thanks for stopping by. Let's build something intelligent together.</i>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:181717,100:0A66C2&height=120&section=footer" width="100%" alt="footer" />
