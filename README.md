<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Dhruvi&fontSize=80&fontColor=ffffff&fontAlignY=38&desc=AI%20%2F%20ML%20Engineer%20%7C%20Full%20Stack%20Developer%20%7C%20Builder&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=22&duration=3500&pause=900&color=8B5CF6&center=true&vCenter=true&multiline=false&repeat=true&width=700&lines=AI+%2F+ML+Engineer+%7C+Deep+Learning+Practitioner;Full+Stack+Developer+%7C+Flask+%2B+React+%2F+Vite;Building+Intelligent+Systems+at+Scale;Insurance+AI+%7C+NLP+%7C+Computer+Vision;B.Tech+CSE+%40+Manipal+University+Jaipur)](https://git.io/typing-svg)

</div>

<br/>

<div align="center">

![B.Tech CSE](https://img.shields.io/badge/B.Tech%20CSE-Manipal%20University%20Jaipur-7C3AED?style=flat-square&logo=graduation-cap&logoColor=white)
![Location](https://img.shields.io/badge/📍-Gurgaon%2C%20India-4C1D95?style=flat-square&logoColor=white)

</div>

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/D-hruvi)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/D-hruvi)

</div>

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=D-hruvi&style=flat-square&color=7C3AED&label=Profile+Views)
![GitHub Followers](https://img.shields.io/github/followers/D-hruvi?style=flat-square&color=6D28D9&label=Followers&logo=github)
![GitHub Stars](https://img.shields.io/github/stars/D-hruvi?style=flat-square&color=5B21B6&label=Stars&logo=github)

</div>

---

## ◈ About

<table>
<tr>
<td>


I am a **third-year Computer Science and Engineering student**, passionate about **Artificial Intelligence, Machine Learning, and Full-Stack Development**. I enjoy building practical AI-powered applications that solve real-world problems, with a strong focus on writing clean, scalable, and maintainable software.

Currently, I am working as an **AI/ML Intern at Fondos Technologies**, where I develop intelligent automation solutions for the insurance domain. My work involves designing AI-assisted data processing pipelines, integrating large language models into production workflows, building Flask-based APIs, and developing React frontends to create complete end-to-end applications.

Beyond my internship, I enjoy exploring **Deep Learning, Generative AI, and Natural Language Processing** while continuously strengthening my foundation in **Data Structures & Algorithms** and software engineering. I believe in learning by building and regularly work on projects that combine machine learning with modern web technologies.


</td>
</tr>
</table>

**Open To** → AI/ML Research Internships · Full Stack Roles · Open Source Collaboration · Research Partnerships

---

## ◈ Tech Stack

<div align="center">

#### Languages
[![My Skills](https://skillicons.dev/icons?i=python,js,c,html,css&theme=dark)](https://skillicons.dev)

#### Frontend
[![My Skills](https://skillicons.dev/icons?i=react&theme=dark)](https://skillicons.dev)

#### Backend & Databases
[![My Skills](https://skillicons.dev/icons?i=flask,fastapi,nodejs,postgres,mongodb&theme=dark)](https://skillicons.dev)

#### AI / ML & Data
[![My Skills](https://skillicons.dev/icons?i=tensorflow,sklearn,jupyter,kafka&theme=dark)](https://skillicons.dev)


---

## ◈ Featured Projects

<details>
<summary><strong>◆ Digit 2W Insurance Commission Converter</strong> — AI-Powered Insurance Data Processing Engine</summary>

<br/>

An enterprise-grade AI pipeline that ingests Indian two-wheeler insurance commission grid Excel files and produces fully structured, schema-compliant payout rule outputs across 37 Indian states. Built with a dual-mode architecture supporting both deterministic rule execution and LLM-driven inference via Groq `llama-3.3-70b-versatile`.

<br/>

| Attribute | Detail |
|:---|:---|
| **Stack** | Python · Flask · React · Vite · Groq API · OpenPyXL · Gunicorn · Render |
| **Scale** | 37 state files · 50-column output schema · 27 business rules · Batch LLM inference |
| **Performance** | Async background job processing · Polling API · Single-worker Gunicorn constraint handled |
| **Security** | Environment-scoped API key management · Input validation · Error-bounded LLM parsing |
| **Impact** | Reduces manual commission mapping from days to minutes · Production-deployed on Render |
| **Repository** | [github.com/D-hruvi](https://github.com/D-hruvi) |

The system encodes 27 domain-specific business rules (RTO clusters, PayIn/POSP commissions, MISP rates, product types — 1+1, 1+5, SAOD, SATP — and vehicle segments including EV, MC, SC) as a structured system prompt. Raw grid rows are batched and sent to the LLM, with outputs parsed, validated, and written to a 50-column Excel schema. A React / Vite frontend with a dark ledger aesthetic provides drag-and-drop upload, live job progress, and per-file or ZIP download.

</details>

<br/>

<details>
<summary><strong>◆ IFFCO CV Vehicle Data Matcher</strong> — Fuzzy Matching Engine for Commercial Vehicle Insurance</summary>

<br/>

A high-throughput fuzzy matching system built to reconcile unstructured vehicle data entries against a master dataset of ~44,000 commercial vehicle records for IFFCO Tokio insurance workflows. Combines LLM-powered semantic understanding with normalisation preprocessing to achieve high-confidence matches at scale.

<br/>

| Attribute | Detail |
|:---|:---|
| **Stack** | Python · Flask · Groq API · pandas · FuzzyWuzzy · React |
| **Scale** | ~44,000 row master dataset · Batch processing · Multi-field matching |
| **Performance** | Preprocessing normalisation layer reduces LLM token load · Configurable confidence thresholds |
| **Security** | Rate-limit-aware batch scheduling · Graceful degradation on API quota exhaustion |
| **Impact** | Automates vehicle classification task previously requiring manual analyst review |
| **Repository** | [github.com/D-hruvi](https://github.com/D-hruvi) |

The matcher operates on a two-stage pipeline: a deterministic normalisation pass (make/model standardisation, fuel type canonicalisation, RTO code parsing) followed by LLM-assisted disambiguation for ambiguous entries. Output is a structured CSV with match scores, candidate ranks, and confidence flags for downstream audit.

</details>

<br/>

<details>
<summary><strong>◆ AI Fake Review Detection System</strong> — NLP Classification for Trust & Safety</summary>

<br/>

A production-deployed NLP pipeline for detecting synthetic and manipulated product reviews using machine learning classifiers trained on linguistic and behavioural feature sets. Deployed on Render and accessible as a live web application.

<br/>

| Attribute | Detail |
|:---|:---|
| **Stack** | Python · scikit-learn · Flask · HTML/CSS · Render |
| **Scale** | Multi-class classification · Real-time inference API |
| **Performance** | TF-IDF vectorisation · Ensemble classifier · Sub-100ms inference |
| **Security** | Input sanitisation · Rate-limited public API |
| **Impact** | Live deployment at pbl-presentation.onrender.com |
| **Repository** | [github.com/D-hruvi](https://github.com/D-hruvi) |

The system extracts lexical, syntactic, and metadata features from review text, feeding them into a trained ensemble classifier. The Flask API supports both single-review and batch prediction endpoints, with a minimal frontend for demonstration.

</details>

<br/>

<details>
<summary><strong>◆ Ford Car Price Prediction</strong> — Regression Modelling on Kaggle</summary>

<br/>

An end-to-end supervised learning project on Kaggle predicting used Ford vehicle resale prices from structured tabular features including mileage, engine size, fuel type, transmission, and year of manufacture.

<br/>

| Attribute | Detail |
|:---|:---|
| **Stack** | Python · pandas · scikit-learn · XGBoost · Matplotlib · Seaborn · Kaggle |
| **Scale** | Structured tabular dataset · Multi-feature regression |
| **Performance** | Feature importance analysis · Cross-validation · RMSE optimisation |
| **Security** | — |
| **Impact** | Published Kaggle notebook with documented methodology |
| **Repository** | [Kaggle — Ford Car Price Prediction](https://www.kaggle.com/) |

The project demonstrates a full data science workflow: exploratory data analysis, outlier treatment, categorical encoding, feature selection, model benchmarking across Linear Regression, Random Forest, and XGBoost, and final model serialisation.

</details>

<br/>

<details>
<summary><strong>◆ Heart Disease Prediction</strong> — Clinical ML Classification</summary>

<br/>

A binary classification system trained on clinical health indicators to predict the probability of cardiovascular disease. Emphasises interpretability and clinical validity of feature selection.

<br/>

| Attribute | Detail |
|:---|:---|
| **Stack** | Python · scikit-learn · pandas · Matplotlib · Flask |
| **Scale** | Clinical tabular dataset · Binary classification |
| **Performance** | Logistic Regression · Random Forest · ROC-AUC evaluation |
| **Security** | No PII in training pipeline |
| **Impact** | Demonstrates responsible ML in high-stakes medical domain |
| **Repository** | [github.com/D-hruvi](https://github.com/D-hruvi) |

Feature engineering focused on clinically validated predictors. Model selection prioritised recall over precision given the asymmetric cost of false negatives in a medical context. Results visualised with ROC curves and confusion matrices.

</details>

---

## ◈ Experience

<table>
<tr>
<td>

### AI / ML Intern — Fondos Technologies (FondosTech)
`2024 – Present` · 

Designing and deploying AI-powered automation systems for the insurance data processing domain. Engineering the full stack from raw Excel ingestion through LLM inference to structured output delivery, with production deployment on cloud infrastructure.

- Architected a dual-mode commission processing engine (deterministic + LLM) for Indian two-wheeler insurance grids
- Integrated Groq `llama-3.3-70b-versatile` via structured prompt engineering encoding 27 business rules
- Built async Flask backend with background job queuing, polling API, and Gunicorn single-worker deployment on Render
- Developed React / Vite frontend with drag-and-drop upload, real-time progress, and multi-file download
- Engineered a fuzzy vehicle matching pipeline against a ~44,000 row master dataset for IFFCO CV workflows
- Debugged and resolved LLM output truncation, JSON parsing failures, TPM rate limiting, and Gunicorn worker timeout issues in production

![Python](https://img.shields.io/badge/Python-7C3AED?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-6D28D9?style=flat-square&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-5B21B6?style=flat-square&logo=react&logoColor=white)
![Groq](https://img.shields.io/badge/Groq%20API-4C1D95?style=flat-square&logoColor=white)
![LLM](https://img.shields.io/badge/LLM%20Engineering-3B0764?style=flat-square&logoColor=white)
![Render](https://img.shields.io/badge/Render-6D28D9?style=flat-square&logo=render&logoColor=white)

</td>
</tr>
</table>

---

## ◈ Achievements

<div align="center">

| Recognition | Details |
|:---:|:---|
| **Production Full-stack Deployment** | Deployed end-to-end AI insurance processing system serving real business workflows at FondosTech |
| **Kaggle Publication** | Published documented ML notebook for Ford Car Price Prediction on Kaggle |
| **Live ML Product** | Fake Review Detection System deployed and publicly accessible on Render |

</div>

---

## ◈ Certifications

<div align="center">


```markdown
#### NPTEL

![Design and Analysis of Algorithms](https://img.shields.io/badge/Design%20%26%20Analysis%20of%20Algorithms-NPTEL-7C3AED?style=for-the-badge&logo=academia&logoColor=white)

![Data Structures and Algorithms using Java](https://img.shields.io/badge/Data%20Structures%20%26%20Algorithms%20using%20Java-NPTEL-6D28D9?style=for-the-badge&logo=openjdk&logoColor=white)

#### Udemy

![Python for Data Science and Machine Learning Bootcamp](https://img.shields.io/badge/Python%20for%20Data%20Science%20%26%20Machine%20Learning%20Bootcamp-Udemy-A435F0?style=for-the-badge&logo=udemy&logoColor=white)

#### Red Hat Academy

![Red Hat System Administration I (RH124)](https://img.shields.io/badge/Red%20Hat%20System%20Administration%20I%20(RH124)-Red%20Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white)
```



</div>

---

## ◈ Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/ETJp2xXbUz/)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/dhruvirohilla)

</div>

---

## ◈ GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=D-hruvi&show_icons=true&theme=midnight-purple&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D0D0D&title_color=8B5CF6&icon_color=7C3AED&text_color=C4B5FD&ring_color=6D28D9"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=D-hruvi&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0D0D0D&title_color=8B5CF6&text_color=C4B5FD&langs_count=8"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com?user=D-hruvi&theme=midnight-purple&hide_border=true&background=0D0D0D&stroke=6D28D9&ring=8B5CF6&fire=7C3AED&currStreakNum=C4B5FD&sideNums=C4B5FD&currStreakLabel=8B5CF6&sideLabels=8B5CF6&dates=6D28D9" />

</div>

---

## ◈ GitHub Trophies

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=D-hruvi&theme=discord&no-frame=true&no-bg=true&margin-w=6&column=7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## ◈ Contribution Activity

<div align="center">

[![Dhruvi's GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=D-hruvi&bg_color=0D0D0D&color=8B5CF6&line=7C3AED&point=C4B5FD&area=true&area_color=6D28D9&hide_border=true&custom_title=Contribution%20Activity)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## ◈ Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/D-hruvi/D-hruvi/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/D-hruvi/D-hruvi/output/github-contribution-grid-snake.svg"/>
  <img alt="github-snake" src="https://raw.githubusercontent.com/D-hruvi/D-hruvi/output/github-contribution-grid-snake-dark.svg"/>
</picture>

</div>

## ◈ Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhruvi.rohilla@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dhruvi-rohilla)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/D-hruvi)
[![Portfolio](https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/D-hruvi)

</div>

---

<div align="center">

*Engineering is not about writing code — it is about solving problems with rigour, clarity, and craft.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer&animation=fadeIn" width="100%"/>

</div>
