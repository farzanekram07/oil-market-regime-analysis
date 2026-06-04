# Oil Market Regime Analysis

A data analytics project focused on understanding crude oil market behavior through volatility analysis, trend persistence, and market regime detection.

---

## Project Objectives

- Analyze historical crude oil price behavior
- Measure volatility and trend persistence
- Detect different market regimes
- Generate actionable market insights
- Build a reproducible analytics workflow

---

## Tech Stack

- Python
- Pandas
- NumPy
- SciPy
- Scikit-Learn
- Matplotlib
- Plotly

---

## Project Structure

```text
oil-market-regime-analysis/
│
├── data/
│   ├── raw/                      # Original downloaded datasets
│   └── processed/                # Cleaned and transformed datasets
│
├── notebooks/
│   ├── 01_data_collection.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   ├── 03_volatility_analysis.ipynb
│   ├── 04_regime_detection.ipynb
│   └── 05_insights_and_recommendations.ipynb
│
├── reports/
│   ├── figures/                  # Generated charts and visualizations
│   └── final_report.md           # Project findings and conclusions
│
├── src/
│   ├── data/
│   │   ├── loader.py
│   │   └── preprocessing.py
│   │
│   ├── features/
│   │   ├── returns.py
│   │   ├── volatility.py
│   │   └── trend.py
│   │
│   ├── analysis/
│   │   ├── volatility_analysis.py
│   │   └── regime_detection.py
│   │
│   ├── visualization/
│   │   ├── plots.py
│   │   └── dashboards.py
│   │
│   └── utils/
│       └── helpers.py
│
├── requirements.txt             # Project dependencies
├── README.md                    # Project documentation
└── .gitignore
```

---

## Analysis Workflow

1. Collect historical crude oil price data
2. Clean and preprocess data
3. Perform exploratory data analysis (EDA)
4. Measure returns and volatility
5. Identify market trends
6. Detect market regimes
7. Generate insights and recommendations

---

## Key Questions

This project aims to answer:

- When does oil market volatility spike?
- How persistent are oil price trends?
- Can market regimes be identified from historical data?
- How do volatility and trends interact?
- What market conditions precede major price movements?

---

## Future Enhancements

- Hidden Markov Models (HMM) for regime detection
- Volatility forecasting with GARCH models
- Interactive dashboards
- Automated reporting pipeline
- Machine learning-based regime classification

---
