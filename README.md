<div align="center">

# Mayur Gaikwad

**AI/ML Engineering Student · Autonomous Systems · LLM Applications**

[![Email](https://img.shields.io/badge/Email-mayurkg15@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:mayurkg15@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mayurgaikwad15-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mayurgaikwad15)
[![GitHub](https://img.shields.io/badge/GitHub-Nighthawk7792-181717?style=flat&logo=github)](https://github.com/Nighthawk7792)

</div>

---

## About

Third-year B.E. student in Artificial Intelligence & Machine Learning at Universal College of Engineering, Mumbai — also enrolled in IIT Patna's Foundations in AI/ML certificate program.

I build end-to-end AI systems: agentic pipelines, RAG-based retrieval systems, computer vision models, and locally-deployable LLM applications. My work sits at the intersection of research-grade ML and production engineering.

---

## Projects

### [F.R.E.D.R.I.N.N. — Autonomous AI Agent](https://github.com/MayurGaikwad-15/F.R.E.D.R.I.N.N)
`Python` `Groq (LLaMA 3.1/3.3)` `Discord.py` `ReAct` `Gmail API` `Google Calendar` `Playwright` `Docker` `SQLite`

A fully autonomous ReAct-loop AI agent operable through Discord with 39+ tools across 8 integrated modules.

- **Dynamic tool router** — keyword-based intent analysis injects only relevant tool schemas per message, reducing LLM token usage by ~80% and enabling 4× more requests/min on Groq's free tier
- **8 real integrations** — Gmail (23 tools: triage, smart drafting, real-time 60s inbox polling), Google Calendar (conflict detection, focus blocks, meeting prep), LinkedIn (OAuth 2.0 UGC publishing), web automation via Playwright headless Chromium, Google Drive smart file routing (<25 MB → Discord, ≥25 MB → Drive link), food ordering (pure regex, zero LLM cost), research intelligence, and file transfer
- **Human-in-the-Loop safety gate** — 5 destructive tools require explicit Discord button approval before execution; persistent multi-turn memory via SQLite WAL mode; containerized with Docker Compose

---

### [Flipkart Order Intelligence & Support Assistant](https://github.com/Nighthawk7792/Flipkart-Order-Intelligence-Support-Assistant)
`Python` `LangGraph` `ResNet-18` `RAG` `Random Forest` `Hugging Face` `all-MiniLM-L6-v2`

A 3-component AI system for e-commerce support combining agentic reasoning, computer vision, and risk classification.

- **LangGraph support agent** — multi-node intent-routing graph (policy queries, tool calls, conversational turns) with RAG retrieval over 14 policy documents achieving avg Recall@3 = 1.0; input/output guardrails with regex injection filtering and cosine-similarity groundedness check (threshold 0.45)
- **ResNet-18 image classifier** — transfer learning pipeline on Fashion-MNIST (70,000 images), frozen ImageNet backbone extracting 512-dim features, achieving **88.39% test accuracy** across 20 epochs
- **Return-risk classifier** — 6 engineered interaction features boosting Random Forest **ROC-AUC to 0.6393 (+2.5 pp vs baseline)** on 6,000 synthetic orders; benchmarked against Logistic Regression and GradientBoosting

---

### Facial Detection & Emotion Classifier
`Python` `OpenCV` `CNN` `Keras` `TensorFlow`

End-to-end real-time computer vision pipeline for face detection and facial expression classification.

- OpenCV Haar cascade face detector feeding a CNN-based emotion classifier
- Full preprocessing pipeline: grayscale conversion, normalization, data augmentation for robustness across lighting and pose variations

---

### House Price Prediction
`Python` `Scikit-learn` `Pandas` `NumPy` `Matplotlib`

Supervised regression pipeline for residential property price prediction.

- Compared Linear Regression, Ridge, and Random Forest regressors with feature engineering (encoding, scaling, outlier treatment)
- EDA-driven feature importance analysis; model validation via cross-validation and RMSE/R²

---

## Technical Skills

| Category | Stack |
|---|---|
| **Languages** | Python, C, C++, SQL, JavaScript |
| **ML / DL** | PyTorch, TensorFlow, Scikit-learn, Keras, Hugging Face, LangGraph, ResNet-18 |
| **Gen AI / LLM** | RAG, ReAct Agents, Prompt Engineering, Vector Embeddings, LLaMA 3.1/3.3, Groq API |
| **Computer Vision** | OpenCV, Transfer Learning, CNN, Image Classification |
| **Data** | NumPy, Pandas, Matplotlib, Seaborn, Power BI |
| **Tools & Infra** | Git, Docker, FastAPI, REST APIs, Playwright, SQLite, Google Colab, AWS, Azure |

---

## Education

**B.E. Artificial Intelligence & Machine Learning**  
Universal College of Engineering, Mumbai · 2023 – 2027

**Foundations in Artificial Intelligence & Machine Learning** *(Certificate Program)*  
Indian Institute of Technology (IIT) Patna · 2025 – 2026

---

## Experience

**Lead ML Intern — We Are Brokers** *(Mumbai)*  
Developed predictive analytics models for client acquisition forecasting; built end-to-end data pipelines and integrated ML models into internal tools; presented AI-driven insights to the founding team influencing product roadmap decisions.

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=MayurGaikwad-15&show_icons=true&theme=default&hide_border=true)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=MayurGaikwad-15&theme=default&hide_border=true)

</div>
