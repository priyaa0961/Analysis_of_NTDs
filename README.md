# Exploratory Data Analysis of Neglected Tropical Diseases (NTDs)

## Overview

This project performs Exploratory Data Analysis (EDA) on the World Health Organization (WHO) Neglected Tropical Diseases (NTDs) dataset to identify trends, patterns, and relationships in disease prevalence across different countries and years.

The analysis includes data preprocessing, visualization, feature engineering, and a basic machine learning model to understand disease patterns and evaluate predictive performance.

---

## Objectives

- Analyze global trends in Neglected Tropical Diseases.
- Understand disease distribution across countries and regions.
- Identify important features influencing disease prevalence.
- Visualize correlations and temporal patterns.
- Build a baseline Random Forest Regression model for analysis.

---

## Dataset

**Source:** World Health Organization (WHO) – Global Health Observatory (GHO)

Diseases included:
- Leprosy
- Rabies
- Buruli Ulcer
- Human African Trypanosomiasis (HAT)

---

## Exploratory Data Analysis

The project includes:

- Data Cleaning
- Handling Missing Values
- Encoding Categorical Variables
- Statistical Summary
- Correlation Matrix
- Feature Importance Analysis
- Disease Trend Visualization
- Country-wise Analysis
- Actual vs Predicted Comparison

---

## Machine Learning

A Random Forest Regressor was implemented as a baseline model to analyze disease trends.

### Evaluation Metrics

- R² Score
- RMSE
- MAE

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Structure

```
NTD-EDA/
│
├── NTD_EDA.ipynb
├── README.md
├── requirements.txt
├── .gitignore
├── images/
│   ├── correlation_matrix.png
│   ├── feature_importance.png
│   ├── disease_trends.png
│   └── actual_vs_predicted.png
└── paper.pdf
```

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/<your-username>/NTD-EDA.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

Run all cells to reproduce the analysis.

---

## Results

- Explored disease trends across multiple regions.
- Identified significant features affecting disease prevalence.
- Visualized relationships between variables.
- Built a baseline Random Forest Regression model for analytical insights.

---

## Future Improvements

- Interactive dashboard using Streamlit
- Time-series forecasting
- Advanced machine learning models
- Real-time WHO data integration

---

## Author

**Priya**
