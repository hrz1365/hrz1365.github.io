---
title: "Projects"
permalink: /projects/
layout: single
author_profile: true
---

Below is a selection of projects that reflect my work in **predictive modeling, LLMs,
simulation, and applied machine learning** for energy, climate, and
public health. Each project emphasizes **decision relevance**
alongside technical rigor.

---

## ⚡ Northeast Freight Corridor Charging Plan

**Focus:** Predictive modeling · Simulation · Energy systems  

Developed forecasting and simulation-based models to support **proactive grid
infrastructure planning** under increasing electrification from EVs.

**Key contributions:**
- Designed, led, and deployed predictive simulation models, with uncertainty quantification enabled,
  using Geotab’s vehicle telematics data across 140 highway plazas in 9 Northeast states, enabling
  National Grid and state utilities to plan multi-megawatt medium- and heavy-duty charging infrastructure
  in support of a national freight electrification strategy  
- Developed a modular system to prepare, process, and visualize data for scalable, reusable analytics
- Co-led the development of a client-facing electrification roadmap, synthesizing technical analysis into
  actionable policy and investment guidance for utilities, regulators, and state agencies  
- Co-led workshops to communicate the insights of the project to various stakeholders, ranging from
  utilities to state representatives in the Northeast 

**Methods & tools:**  
Python, Monte Carlo Simulation, Vehicle Telematics Data, Forecasting, Datawrapper  

**Outcome & Impact:**  
- Enabled planners to assess grid readiness
- Located areas that need prioritized investment
- Identified potential constraints
- Compared investment strategies under uncertainty

🔗 [Project Link](https://www.nationalgrid.com/us/EVhighway)
🔗 [Full Report Link](https://www.nationalgrid.com/document/566386/download)
🔗 [Summary Link](https://www.nationalgrid.com/document/566391/download)

---

## 🧠 EVRAG — Large Language Models for Interpretation *(Side Project)*

**Focus:** LLMs · RAG · Decision support

Developed a **Retrieval-Augmented Generation (RAG)** system to assist with
interpreting and communicating insights from technical EV charging reports.

This project treats language models as a **supporting layer** — augmenting
quantitative modeling rather than replacing it.

**Key contributions:**
- Built a modular RAG pipeline grounded in domain-specific documents  
- Implemented evaluation metrics to assess faithfulness, relevance, and
  correctness  
- Integrated the system into a workflow for summarizing and contextualizing
  technical analyses
- Containerized and operationalized the pipeline using Docker, with CI/CD automation via GitHub Actions and an interactive Streamlit interface  

**Methods & tools:**  
Python, LangChain, FAISS, Transformers, DeepEval, Docker, Github Actions  

**Outcome:**  
Improved accessibility and interpretation of complex modeling outputs for
technical and non-technical audiences.

🔗 [GitHub Repository](https://github.com/hrz1365/evrag)

---

## 🌆 NYC Climate Vulnerability Modeling

**Focus:** Spatiotemporal modeling · Deep learning · Simulation  

Led the development of **high-resolution spatiotemporal models** to analyze population
vulnerability to climate impacts across New York City.

**Key contributions:**
- Designed spatial feature engineering pipelines for demographic data  
- Applied deep learning (LSTM-based models) to capture temporal and spatial
  dynamics  
- Produced high-resolution projections by age and race to support climate vulnerability 
  analysis in NYC 

**Methods & tools:**  
Python (rasterio, multiprocessing), R (sf, terra, tidyverse), TensorFlow  

**Outcome & impact:**  
Generated decision-ready insights for climate adaptation planning; work accepted
for publication (in-press) in *Proceedings of the National Academy of Sciences (PNAS)*.

🔗 [Project Link](https://researchdiscovery.drexel.edu/esploro/outputs/991021892215604721)
🔗 [GitHub Repository](https://github.com/hrz1365/NYC_Project)

---

## 🦠 AI-enabled COVID-19 forecasting

**Focus:** Predictive analytics · Time Series Analysis · Public Health   

Co-led a collaborative effort to develop **AI-enabled forecasting models** for
weekly COVID-19 incidence rates at the U.S. county level across multiple
forecast horizons, with explicit uncertainty quantification..

**Key contributions:**
- Designed end-to-end machine learning workflows spanning data ingestion,
  feature engineering, model training, and validation  
- Developed and evaluated several AI-based forecasting models using gradient
  boosting and deep learning  
- Integrated spatial and temporal dimensions to support regional planning
- Implemented uncertainty-aware evaluation across short- and medium-term
  forecast horizons

**Methods & tools:**  
XGBoost, LSTM models, scikit-learn, TensorFlow, time-series feature engineering,
uncertainty evaluation 

**Outcome & impact:**
- Ranked among the top 5 most accurate forecasting models in the
  U.S. COVID-19 Forecast Hub
- Delivered improvements of up to 50 cases per county relative to the
  COVIDhub ensemble used by CDC decision-makers
- Contributed to real-time forecasting efforts supporting national public
  health planning

🔗 [Paper 1 Link](https://www.nature.com/articles/s41467-021-26742-6)
🔗 [Paper 2 Link](https://www.nature.com/articles/s41597-022-01517-w)

---

## 🧩 Common Themes Across Projects

- Emphasis on **predictive and simulation-based modeling**  
- Integration of **spatial and temporal context**  
- Explicit treatment of **uncertainty and scenarios**  
- Focus on **decision support**, not just prediction accuracy  
