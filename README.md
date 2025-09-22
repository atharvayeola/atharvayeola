# Atharva Yeola

Hey! I'm **Atharva Yeola** — a data scientist and machine learning engineer who loves shipping end‑to‑end AI systems. I blend **agentic LLMs**, **NLP**, **computer vision**, and **product analytics** to turn messy data into clear, usable tools. From public‑health dashboards to edge‑deployed CV systems, I care about solutions that are **reliable, reproducible, and useful**.

> 🎯 Mission: build practical AI that stands up in the wild — measurable impact, clean interfaces, and honest evaluations.

---

## 🔗 Quick Links

- 🌐 **Website:** [atharvayeola.com](https://www.atharvayeola.com)
- 💼 **LinkedIn:** [/in/atharvayeola](https://linkedin.com/in/atharvayeola)
- 📨 **Email:** atharvayeola12@gmail.com
- 🧪 **GitHub:** [/atharvayeola](https://github.com/atharvayeola)

---

## 📚 Table of Contents

- [Agentic AI Work](#agentic-ai-work)
- [Natural Language Processing](#natural-language-processing)
- [Computer Vision](#computer-vision)
- [Data Science & Analytics](#data-science--analytics)
- [Other Work](#other-work)
- [Publications](#publications)
- [Skills & Tools](#skills--tools)

---

## 🧠 Agentic AI Work

Personal focus: **reliable, inspectable, and benchmarked agents** — not just demos.

### BenchAgent — LangChain + MCP Eval Agent
- **What:** An MCP-compliant agent that runs end‑to‑end evaluation pipelines (datasets × metrics), logs **100%** predictions/metrics to JSON/SQLite, and compares models (e.g., *GPT‑4o‑mini*, *Claude 3 Haiku*, *open models*).
- **Why it matters:** Keeps experiments *reproducible* and accelerates iteration via a FastAPI‑triggered React cockpit.
- **Status:** Active project (shipping soon).  
- **Repo:** _Coming soon (placeholder)_

### Waldo — Adverse Event Detection Agent (RoBERTa)
- **What:** An open-sourced pipeline that flags **adverse events** in unstructured text (Reddit), with rare‑class metrics and failure mode analysis.
- **Stack:** PyTorch, Hugging Face, custom evaluation harness.
- **Outcome:** Informed public‑health analysis around sports betting impact (see JAMA paper below).
- **Repo:** _Internal research code (summary here); public components rolling out soon._

### Model Eval Agent (baseline)
- **What:** Lightweight model evaluation harness (metrics, confusion matrices, artifacts) for **LLM output benchmarking**.
- **Repo:** [atharvayeola/model_eval_agent](https://github.com/atharvayeola/model_eval_agent)

> 🔜 *More agentic systems coming — tool‑use planners, guardrail experiments, and retrieval‑heavy agents.*

---

## 🗣️ Natural Language Processing

### Adverse Event Detection (RoBERTa, Reddit)
- **What:** Fine‑tuned **RoBERTa** on 360K+ posts to detect adverse events in noisy text.
- **Why:** Early warning signals for public health; contributed to quantifying gambling‑addiction shifts post U.S. sportsbook legalization.
- **Stack:** PyTorch, Transformers, custom rare‑class evaluation.
- **Impact:** Helped quantify a ~23% **increase** in addiction‑related risk signals (see publication).

### Summarization + MLOps
- **What:** End‑to‑end summarizer with adjustable decoding, evaluation harness (ROUGE), and CI/CD deploys.
- **Stack:** Hugging Face, Flask/FastAPI, Docker, GitHub Actions, AWS.
- **Outcome:** Reproducible runs with CSV/JSON artifacts and logs for audit‑ready comparisons.

> 📌 *I like NLP work that ships: clean APIs, metrics you can trust, and dashboards that make results obvious.*

---

## 👁️ Computer Vision

### RetailLens — Real‑Time Shelf Intelligence
- **What:** Real‑time shelf analytics with **YOLOv8** + **SuperGlue** for fine‑grained product ID.
- **Impact:** ~80% mAP in testing; robust edge deployment for varied store layouts and lighting.
- **Stack:** YOLOv8, OpenCV, Docker; telemetry → dashboards.
- **Repo:** [atharvayeola/retail-vision-enhancement](https://github.com/atharvayeola/retail-vision-enhancement)
- **Media:** _Add demo GIF/screenshot here_ (`/assets/retaillens-demo.gif`)

### Occluded Traffic Sign Recognition (IIT Patna, Research)
- **What:** Deep ensemble (**ViT + EfficientNet**) with occlusion‑aware training + synthetic data boost (+30% dataset).
- **Impact:** +9% F1 over baselines; stronger long‑tail precision.
- **Paper:** IEEE CVMI 2024 — _Enhancing Traffic Sign Recognition: A Deep Learning Approach for Occluded Environments_  
  Link: https://ieeexplore.ieee.org/document/10782104
- **Media:** _Add figure or results plot_

### MediSyn‑Vision — Synthetic Medical Imaging (Prototype)
- **What:** Diffusion/LoRA pipeline to generate domain‑specific synthetic images; tracked **KID** and **TSTR** metrics.
- **Repo:** [atharvayeola/SynMedVision](https://github.com/atharvayeola/SynMedVision)
- **Media:** _Add training samples / side‑by‑side_

### Edge CV @ Atomic Loops
- **What:** Deployed **YOLOv5** on Raspberry Pi for conveyor analytics; synchronized model latency with hardware.
- **Impact:** ~98% detection precision; ~30% footfall lift; ~12% MoM revenue boost.
- **Media:** _Add short pipeline diagram_

---

## 📊 Data Science & Analytics

### HIVTrends.org — Public Health Signals
- **What:** Live dashboard tracking weekly uptake of at‑home HIV test kits.
- **Impact:** Adopted by product & public‑health partners; informs campaign budgets.
- **Repo/Link:** https://hivtrends.org
- **Media:** _Add dashboard screenshot_

### CommerceFlow — E‑commerce Funnel Analysis
- **What:** PySpark pipeline over **2M+** events; mapped view → cart → purchase, cohort & RFM analytics, Holt‑Winters forecast.
- **Insight:** Identified **96%** drop‑off from cart to purchase → drove conversion strategy.
- **Repo:** [atharvayeola/ecommerce-funnel-analysis](https://github.com/atharvayeola/ecommerce-funnel-analysis)
- **Media:** _Add funnel chart / retention heatmap_

### Superstore Analytics Pipeline
- **What:** Medallion (Bronze→Silver→Gold) ETL + **star schema** (SQLite) + **Dash** app.
- **Why:** Daily automation, top‑customers, margins, trends — all self‑serve.
- **Repo:** [atharvayeola/superstore-analytics-pipeline](https://github.com/atharvayeola/superstore-analytics-pipeline)
- **Media:** _Add dashboard GIF_

### Social Media Engagement Insights (Power BI)
- **What:** Cross‑platform engagement analytics (12B+ views; filters by region/platform/type).
- **Repo:** [atharvayeola/social-media_engagement-insights](https://github.com/atharvayeola/social-media_engagement-insights)
- **Media:** _Add PBIX screenshots_

> 🧪 Also into A/B testing, causal inference, MMM‑style thinking, and experiment tracking that PMs can actually use.

---

## 🧩 Other Work

### Data Engineering @ San Diego Natural History Museum
- **What:** Unified 2M+ specimen records from MS Access into MySQL via **dbt**; designed **star schema** for biodiversity analytics across 6+ departments.
- **Impact:** ~40% fewer pipeline errors (field‑level tests); **1.5×** faster curator queries.
- **Stack:** dbt, SQL, Airflow‑style orchestration, CI/CD.
- **Repo:** _Private (institutional); architecture notes coming soon._

### EngageSphere — Product Engagement Platform *(Ideation)*
- **What:** Plug‑and‑play platform for funnels, cohorts, and causal analysis — built for PMs and analysts.
- **Status:** Design notes + prototype in progress.
- **Repo:** _Placeholder_

---

## 📄 Publications

- **JAMA Internal Medicine** — Statistical investigation on gambling‑addiction trends post U.S. sportsbook legalization.  
  Link: https://jamanetwork.com/journals/jamainternalmedicine/fullarticle/2830019
- **IEEE Xplore (CVMI 2024)** — _Enhancing Traffic Sign Recognition: A Deep Learning Approach for Occluded Environments_.  
  Link: https://ieeexplore.ieee.org/document/10782104

---

## 🛠️ Skills & Tools

### Languages & ML
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?logo=apachespark&logoColor=white)

### Data Engineering
![dbt](https://img.shields.io/badge/dbt-FF694B?logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?logo=googlebigquery&logoColor=white)
![Redshift](https://img.shields.io/badge/Redshift-8C4FFF?logo=amazonredshift&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?logo=snowflake&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)

### Visualization & Apps
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white)
![Dash](https://img.shields.io/badge/Dash-1F2636?logo=plotly&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?logo=tableau&logoColor=white)
![PowerBI](https://img.shields.io/badge/PowerBI-F2C811?logo=powerbi&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)

### Cloud, DevOps & Ops
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-1a73e8?logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub_Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

---

## 🙌 Want to Collaborate?
If you’re building in **agentic AI**, **evaluation frameworks**, **vision on the edge**, or **experimentation/causal analytics**, ping me on [LinkedIn](https://linkedin.com/in/atharvayeola) or email me at **atharvayeola12@gmail.com**. Always happy to jam on ideas or pair up on open source.

---

- [ ] Add demo space in `assets/` and link here.

