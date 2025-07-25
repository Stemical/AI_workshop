# AI Workshop: <br> Artificial Intelligence Algorithms for Everyone

**Short-course & Hands-on Workshop**  <br> 
**Dates:** June 23–26, 2025 <br> 
**Instructor:** Dr. R.M. (Rolando) Gonzales Martinez<br> 

---

## Overview

This repository contains all materials for the four-day workshop covering:

- **Introduction to AI & Python** (homogenization; history from automata to singularity)  
- **Machine Learning Algorithms** (elastic nets, XGBoost, neural nets, SVMs, random forests; time-series forecasting with Prophet & LSTM; model evaluation & Bayesian hyper-tuning)  
- **Deep Learning & Recent Trends** (Transformers & LLMs, RoBERTa-based sentiment analysis; ethical considerations; liquid nets; DeepSeek; quantum computing)  
- **Practical Applications & Presentations** (MPS for child mortality; AI in space navigation; credit scoring; demographic forecasts; AI therapists; spatial ML; literature reviews with GPTs)

---

## Schedule (CET)

| Day       | Topics                                                                                                                   |
|-----------|--------------------------------------------------------------------------------------------------------------------------|
| **Mon 23**| • History of AI (automata → deep nets → human-level AI)  <br> • Python for AI & Elastic Nets                              |
| **Tue 24**| • Classification & regression: Elastic Nets, XGBoost, ANN, SVM, RF  <br> • Time-series with Prophet & LSTM  <br> • Feature engineering, model evaluation, Bayesian tuning |
| **Wed 25**| • Deep learning & Transformers  <br> • RoBERTa semantic/sentiment analysis  <br> • Ethics & mitigation strategies  <br> • Advances: liquid nets, DeepSeek, spatial ML, quantum |
| **Thu 26**| • Participant presentations: <br>   – Child mortality via MPS (Kassoum Dianou)  <br>   – AI for autonomous space navigation (Duna Meya i Mendoza) |

Practical demos: AI therapists, credit scoring, demographic forecasting, literature reviews, local LLMs

Each day is split into three 45-minute sections with breaks:  
- Section 1: 14:30–15:15  | Break: 15:15–15:30  
- Section 2: 15:30–16:15  | Break: 16:15–16:30  
- Section 3: 16:30–17:00  | Q&A: 17:00–17:30

---

## Repository Structure

```text
AI_workshop/
├── 01_presentations/                # Slide decks ( .pdf)
├── 02_databases/                    # Sample data files
├── 03_python_scripts/               # .py Jupyter notebooks
│   └──day_1/
│       ├── aiw_00_elizaAI.ipynb     # ELIZA-style AI therapist
│       ├── aiw_01_salaries.ipynb    # OLS & Elastic Nets
│       ├── aiw_02_credit.ipynb      # Credit scoring with logistic models
│       └── aiw_03_creditlm.ipynb    # Credit scoring with Elastic nets
│   └──day_2/
│       ├── aiw_creditML01.ipynb     # Support vector machine
│       ├── aiw_creditML01.ipynb     # SVM, XGBoost, random forests
│       ├── aiw_creditML01.ipynb     # k-fold cross-validation
│       ├── aiw_creditML01.ipynb     # Feature selection
│       └── aiw_creditML01.ipynb     # Tuning of hyper-parameters
├── 04_additional_lectures/          # Papers, books, extra readings
└── README.md                        # This file

