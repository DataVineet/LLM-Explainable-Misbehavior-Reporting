# LLM-Assisted Explainable Misbehavior Reporting Framework

## Summer Research Internship 2026

---

# Student

**Vineet Yadav**

M.Sc. Computer Science (Big Data Analytics)

Department of Data Science & Analytics

Central University of Rajasthan

---

# Research Guide

**Dr. Jyoti Grover**

Assistant Professor

Department of Computer Science & Engineering

Malaviya National Institute of Technology (MNIT), Jaipur

---

# Project Objective

This research aims to develop an Explainable Artificial Intelligence (XAI) framework for vehicular misbehavior detection in Cooperative Intelligent Transportation Systems (C-ITS) using the VeReMi dataset.

The framework integrates:

- Machine Learning based Misbehavior Detection
- Explainable AI using SHAP
- Large Language Models (LLMs)
- Automated Human-Readable Misbehavior Reports

The final goal is to build a reproducible end-to-end pipeline capable of detecting malicious vehicular messages while generating interpretable explanations suitable for researchers, transportation authorities, and cybersecurity analysts.

---

# Repository Structure

```
Research Internship/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── samples/
│
├── notebooks/
│   ├── 01_Dataset_Inspection.ipynb
│   ├── 02_EDA.ipynb
│   ├── 03_Preprocessing_FeatureEngineering.ipynb
│   └── 04_Baseline_Models.ipynb
│
├── outputs/
│   ├── figures/
│   ├── logs/
│   ├── metrics/
│   └── reports/
│
├── models/
│   ├── baseline_models/
│   ├── preprocessing/
│   ├── explainability/
│   ├── saved_models/
│   └── shap_values/
│
├── src/
│
├── docs/
│
├── journals/
│
├── requirements.txt
│
└── README.md
```

---

# Dataset Information

**Dataset:** VeReMi Dataset (Vehicular Reference Misbehavior Dataset)

### Original Dataset

- Total Samples: **22,165,610**
- Multiple Attack Categories
- Binary Attack Label
- Vehicle Position, Speed, Acceleration and Heading Information

### Working Dataset

- Sample Size: **100,000 observations**
- Used for rapid experimentation and model development
- Entire pipeline designed to scale directly to the complete 22-million-record dataset

> The original dataset is intentionally excluded from GitHub because of its size (~7 GB).

---

# Project Workflow

```
Raw Dataset
      │
      ▼
Dataset Inspection
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Feature Scaling
      │
      ▼
Train-Test Split
      │
      ▼
Baseline Machine Learning Models
      │
      ▼
Advanced Models
      │
      ▼
Explainability (SHAP)
      │
      ▼
LLM-based Report Generation
```

---

# Current Progress

## Phase 1 — Dataset Understanding ✅

Completed

- Repository Setup
- Virtual Environment Configuration
- GitHub Integration
- VeReMi Dataset Download
- Sample Dataset Creation
- Dataset Inspection
- Dataset Statistics
- Missing Value Analysis

---

## Phase 2 — Exploratory Data Analysis ✅

Completed

- Statistical Summary
- Data Type Analysis
- Class Distribution
- Attack Type Distribution
- Histograms
- Boxplots
- Correlation Heatmap
- Outlier Analysis
- Variance Analysis
- Feature Importance Exploration
- Correlation Study
- Visualization Export

---

## Phase 3 — Preprocessing & Feature Engineering ✅

Completed

- Data Cleaning
- Feature Engineering
- Magnitude Feature Construction
- Feature Scaling (StandardScaler)
- Train-Test Split
- Metadata Generation
- Feature Name Preservation
- Preprocessing Artifact Saving
- Processed Dataset Generation

---

## Phase 4 — Baseline Machine Learning 🚧

Completed

### Logistic Regression

- Model Training
- Model Evaluation
- ROC-AUC
- Confusion Matrix
- Classification Report

### Decision Tree

- Model Training
- Hyperparameter Configuration
- Feature Importance
- Decision Tree Visualization
- Model Evaluation
- Confusion Matrix
- Classification Report

---

# Upcoming Phases

### Phase 5

- Random Forest Classifier

### Phase 6

- XGBoost Classifier

### Phase 7

- Model Comparison
- Hyperparameter Tuning
- Cross Validation

### Phase 8

- SHAP Explainability
- Global Explanations
- Local Explanations

### Phase 9

- LLM-Based Misbehavior Report Generation
- Human-Readable Attack Explanation

### Phase 10

- Full Dataset Training (22 Million Records)
- Research Paper Preparation
- Final Project Documentation

---

# Models Completed

| Model | Status |
|--------|--------|
| Logistic Regression | ✅ |
| Decision Tree | ✅ |
| Random Forest | ⏳ |
| XGBoost | ⏳ |

---

# Feature Engineering

The following engineered features were created:

- Position Magnitude
- Speed Magnitude
- Acceleration Magnitude
- Heading Magnitude

The preprocessing pipeline also includes:

- Standard Scaling
- Train-Test Split
- Metadata Saving
- Feature Name Preservation

---

# Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- SHAP
- Jupyter Notebook
- VS Code
- Git
- GitHub

---

# Current Status

| Phase | Status |
|--------|--------|
| Phase 1 – Dataset Understanding | ✅ Completed |
| Phase 2 – Exploratory Data Analysis | ✅ Completed |
| Phase 3 – Preprocessing & Feature Engineering | ✅ Completed |
| Phase 4 – Baseline Models | 🚧 In Progress |
| Phase 5 – Random Forest | ⏳ |
| Phase 6 – XGBoost | ⏳ |
| Phase 7 – Explainability | ⏳ |
| Phase 8 – LLM Report Generation | ⏳ |
| Phase 9 – Full Dataset Evaluation | ⏳ |
| Phase 10 – Research Paper | ⏳ |

---

# Repository Notes

- The project follows a modular research-oriented workflow.
- All figures, metrics, reports and trained models are saved in dedicated folders.
- Every notebook is self-contained and reproducible.
- The final pipeline is designed to scale from the 100k sample to the complete VeReMi dataset containing over 22 million records.

---

## Research Status

**Current Milestone Achieved**

✔ Dataset Understanding

✔ Exploratory Data Analysis

✔ Feature Engineering

✔ Logistic Regression Baseline

✔ Decision Tree Baseline

🚧 Next Milestone: Random Forest Classifier