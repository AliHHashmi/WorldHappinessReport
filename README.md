# World Happiness Report: A Decade of Wellbeing

An end-to-end analysis of global happiness trends from 2015 to 2025, using data from the World Happiness Report. The project examines which factors drive national wellbeing, how COVID reshaped the global happiness landscape, and applies machine learning to predict 2026 happiness scores — validated against held-out 2025 actuals.

## Key Findings

- **Global happiness was resilient** — COVID did not cause the expected collapse in scores
- **GDP, social support, and life expectancy** consistently drive happiness across all years
- **The G7 average ranks ~10–15th globally** — wealth alone does not guarantee wellbeing
- **Canada has fallen significantly** in the rankings since 2015 — the model projects a partial recovery in 2026

## Stack

- **Python** — core analysis
- **DuckDB** — in-process SQL querying
- **Pandas** — data transformation and cleaning
- **Plotly** — interactive visualizations
- **Scikit-learn / XGBoost** — Random Forest, XGBoost, and Linear Regression models
- **Jupyter** — notebook environment

## Data Source

World Happiness Report data via [Kaggle](https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2021)

## Live Demo

Charts and findings are embedded in the live portfolio at [my-portfolio-4a705.web.app](https://my-portfolio-4a705.web.app)

## Structure

```
WorldHappinessReport/
├── data/                  # Raw and cleaned datasets
├── public/charts/         # Exported Plotly HTML charts
└── Happiness Report EDA.ipynb  # Full analysis notebook
```
