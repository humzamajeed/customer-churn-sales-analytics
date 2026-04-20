# Customer Churn & Sales Performance Analytics

## Project Overview
An end-to-end data analytics project analyzing customer churn for a telecom company.
This project covers the full analytics pipeline — from exploratory data analysis and
statistical testing to regression modeling and machine learning.

## Business Problem
> "Why are customers churning, and what customer profile is most at risk?"

Understanding churn helps businesses take proactive retention steps and allocate
marketing budgets more effectively.

## Dataset
- **Source:** IBM Telco Customer Churn (via Kaggle)
- **Size:** 7,043 customers × 21 features
- **Target Variable:** `Churn` (Yes / No)
- **Key Features:** Tenure, MonthlyCharges, Contract type, PaymentMethod, Services used

## Tech Stack
| Tool | Purpose |
|------|---------|
| Python | EDA, Regression, ML |
| R | Statistical Testing, ggplot2 Visualizations |
| Jupyter Notebook | Python analysis |
| RMarkdown / Quarto | R analysis & reports |
| GitHub | Version control |

## Project Structure
\```
customer-churn-sales-analytics/
├── data/
│   ├── raw/              # Original dataset
│   └── cleaned/          # Preprocessed data
├── notebooks/            # Jupyter & RMarkdown notebooks
├── scripts/              # Reusable Python scripts
├── outputs/
│   ├── figures/          # Saved plots
│   └── model_metrics/    # Model evaluation results
└── README.md
\```

## Phases
- [x] Phase 1 — Project Setup & Data Sourcing
- [x] Phase 2 — Exploratory Data Analysis (Python)
- [x] Phase 3 — Statistical Analysis (R)
- [x] Phase 4 — Regression Analysis (Python)
- [x] Phase 5 — Machine Learning Models (Python)
- [x] Phase 6 — Advanced Visualizations (R)

## How to Run
1. Clone this repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open notebooks in order starting from `notebooks/01_eda_python.ipynb`
