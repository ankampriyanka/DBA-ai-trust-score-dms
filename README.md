> **Portfolio focus:** Doctoral Research · Trustworthy AI · Automotive AI · Driver Monitoring Systems
>
> Canonical doctoral research repository for the AI Trust Score work evaluating DMS trustworthiness across technical and responsible-AI dimensions.

---

# AI Trust Score DMS

DBA - Walsh MS Capstone Project

## Project Structure

```text
ai-trust-score-dms/
│
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
├── environment.yml
│
├── data/
│   ├── raw/
│   ├── interim/
│   ├── processed/
│   ├── external/
│
├── notebooks/
│   ├── 01_dataset_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda.ipynb
│   ├── 04_feature_engineering.ipynb
│   ├── 05_baseline_models.ipynb
│   ├── 06_ai_trust_score.ipynb
│
├── src/
│   ├── data/
│   ├── features/
│   ├── models/
│   ├── evaluation/
│   ├── visualization/
│   ├── trustscore/
│
├── configs/
│
├── reports/
│   ├── figures/
│   ├── tables/
│
├── outputs/
│   ├── models/
│   ├── metrics/
│   ├── predictions/
│
├── docs/
│
└── tests/
```

## Overview

This repository is organized to support an end-to-end AI trust score project, including data preparation, exploratory analysis, feature engineering, model development, evaluation, and reporting.

## Directory Descriptions

- `data/`: raw, intermediate, processed, and external datasets
- `notebooks/`: project notebooks for each step of the analysis workflow
- `src/`: reusable source code organized by functional area
- `configs/`: configuration files for pipelines and experiments
- `reports/`: generated figures and summary tables
- `outputs/`: saved models, metrics, and prediction outputs
- `docs/`: project documentation and design notes
- `tests/`: automated tests
