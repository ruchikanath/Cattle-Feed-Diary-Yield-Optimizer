# Cattle Feed & Dairy Yield Optimisation System

### An AI-Powered Decision Support System for Dairy Cattle Feed Formulation and Profit Optimisation

## Project Overview

The **Cattle Feed & Dairy Yield Optimisation System** is an intelligent decision-support platform designed to support dairy farmers and livestock management professionals in developing cost-effective and nutritionally balanced cattle feed formulations.

The system combines Machine Learning, nutritional analysis, predictive modelling and mathematical optimisation to support informed decisions on feed composition, milk yield prediction and profitability.

It integrates a stacked-ensemble machine learning approach for milk yield prediction with a Linear Programming-based optimisation engine for feed formulation and cost optimisation.

The project also includes an interactive dashboard to make analytical results and optimisation outputs accessible through a user-friendly interface.

## Key Objectives

- Develop machine learning models to predict dairy cattle milk yield.
- Analyse the relationship between feed composition, nutritional parameters and milk production.
- Formulate nutritionally balanced cattle feed at optimised cost.
- Apply mathematical optimisation to identify suitable feed combinations.
- Evaluate economic trade-offs between feed cost and expected productivity.
- Provide explainable insights to support data-driven decision-making.

## System Architecture

The project integrates four major functional components:

### 1. Milk Yield Prediction

A machine learning pipeline designed to estimate milk yield using relevant cattle and feed-related parameters.

The modelling workflow includes:

- Data preprocessing and feature preparation.
- Training and evaluation of multiple machine learning models.
- Ensemble learning for improved predictive performance.
- Comparison of model predictions and evaluation metrics.

**Machine Learning models explored:**
- Ridge Regression
- Lasso Regression
- XGBoost
- LightGBM
- Stacked Ensemble Learning

### 2. Feed Formulation and Optimisation

A mathematical optimisation engine designed to identify suitable feed combinations while considering nutritional requirements and formulation costs.

The optimisation workflow includes:

- Nutritional constraint definition.
- Feed ingredient selection.
- Cost-based optimisation.
- Evaluation of nutrient composition.
- Identification of feasible feed formulations.

Linear Programming is used to formulate the feed optimisation problem.

### 3. Profit Optimisation and Explainability

The project incorporates economic optimisation and model interpretation to support better decision-making.

Key capabilities include:

- Evaluation of feed formulation costs.
- Analysis of profitability-related parameters.
- SHAP-based model explainability.
- Interpretation of important predictive features.
- Comparison of alternative optimisation outcomes.

### 4. Interactive Decision Support Dashboard

An interactive dashboard provides access to the underlying prediction and optimisation functionalities.

The dashboard includes supporting modules for:

- Milk yield prediction.
- Feed and nutritional data analysis.
- Feed formulation and optimisation.
- Nutritional matrix-based analysis.
- Decision support and result interpretation.

## Technology Stack

| Category | Technologies |
|---|---|
| Programming | Python |
| Machine Learning | Scikit-learn, XGBoost, LightGBM |
| Ensemble Learning | Stacked Regression |
| Optimisation | Linear Programming, PuLP |
| Explainable AI | SHAP |
| Data Processing | Pandas, NumPy |
| Visualisation | Data visualisation libraries |
| Development | Jupyter Notebook |
| Interface | Interactive Dashboard |

## Repository Structure

```text
Cattle-Feed-Diary-Yield-Optimizer/
│
├── dashboard/
│   ├── backend.py
│   ├── model_core.py
│   ├── data/
│   ├── static/
│   ├── requirements.txt
│   └── README.md
│
├── Milk Yield Predictor.ipynb
├── Optimisation Engine_v1.ipynb
├── Optimisation Engine_v2_POC.py
├── Optimisation Engine_v3.py
├── profit_optimizer.py
│
└── README.md
```

## Project Workflow

1. **Data Preparation:** Prepare cattle, feed and nutritional information for analysis.
2. **Predictive Modelling:** Train and evaluate machine learning models for milk yield prediction.
3. **Nutritional Analysis:** Define feed ingredient composition and nutritional requirements.
4. **Optimisation:** Apply mathematical optimisation to identify suitable feed formulations.
5. **Economic Evaluation:** Analyse feed costs and profitability-related outcomes.
6. **Decision Support:** Present predictions and optimisation results through the interactive dashboard.

## Applications

- Dairy farm management and planning.
- Cost-effective cattle feed formulation.
- Milk yield prediction and analysis.
- Nutritional decision support.
- Feed cost and profitability assessment.
- Data-driven livestock management.

## Research and Development Scope

The project demonstrates the integration of predictive machine learning and mathematical optimisation in an agricultural decision-support application.

It provides a foundation for further development in:

- Precision livestock farming.
- AI-driven nutritional recommendations.
- Multi-objective feed and profit optimisation.
- Explainable machine learning for agricultural applications.
- Intelligent dairy farm management systems.

## Future Enhancements

- Integration of real-time dairy farm data.
- Advanced multi-objective optimisation considering nutrition, cost and productivity.
- Enhanced explainability and model interpretation.
- Automated feed recommendation capabilities.
- Cloud-based deployment and scalable decision-support services.

## Author

**Ruchika Nath**

AI/ML Engineer | Machine Learning | Optimisation | Explainable AI

GitHub: [https://github.com/ruchikanath](https://github.com/ruchikanath)

LinkedIn: [https://linkedin.com/in/ruchika-nath-164924195](https://linkedin.com/in/ruchika-nath-164924195)

---

*This project is intended for research, experimentation and decision-support applications in dairy cattle feed formulation and yield optimisation.*
