# Online Gaming Behaviour Analysis

## Project Overview
This project explores online gaming behaviour using data analytics, statistical hypothesis testing, and machine learning. It investigates player activity patterns and identifies behavioural factors that may help explain differences between players.

The aim is to turn gaming data into meaningful insights that can support data-driven business decisions.

## Objectives
- Explore player behaviour and gaming activity patterns.
- Analyse relationships between player characteristics and gaming behaviour.
- Apply statistical tests to evaluate differences and associations in the data.
- Compare machine learning models using appropriate evaluation metrics.
- Identify important behavioural features influencing model predictions.
- Explore potential applications for player engagement and retention strategies.

## Methodology
1. **Data Exploration:** Examine the dataset, understand its variables, and identify patterns.
2. **Statistical Analysis:** Apply tests such as the Kruskal–Wallis test and chi-square test where appropriate.
3. **Machine Learning:** Train and compare classification models, including Decision Tree, Random Forest, Logistic Regression, K-Nearest Neighbours, and Support Vector Machine.
4. **Model Evaluation:** Evaluate model performance using accuracy and macro F1-score, including comparison against a baseline model.
5. **Feature Importance:** Use permutation importance to identify the variables contributing most to model predictions.
6. **Business Interpretation:** Translate analytical findings into potential insights for understanding player behaviour.

## Tools and Technologies
- Python
- Pandas and NumPy
- Scikit-learn
- Statistical hypothesis testing
- Data analysis and visualisation
- Jupyter Notebook

## Key Findings
- The Decision Tree model achieved approximately **90.16% test accuracy** and a **0.8963 test macro F1-score** in the current evaluation.
- The model substantially outperformed the most-frequent-class baseline on macro F1-score.
- Sessions per week, average session duration, and achievements unlocked were among the most important features according to permutation importance.

*Results reflect the current model evaluation and should be interpreted in the context of the dataset and prediction target.*

## Business Applications
The analysis demonstrates how player behaviour data can potentially support:
- Player engagement analysis
- Behaviour-based player profiling
- Retention strategy development
- Data-informed gaming product decisions

## Repository Contents
- `Gaming Behavior.ipynb` — Jupyter Notebook containing the analysis and modelling workflow.

## Author
**Ritika Saini**

This project was developed as part of my data analytics portfolio to apply statistical analysis and machine learning to a real-world-style behavioural data problem.
