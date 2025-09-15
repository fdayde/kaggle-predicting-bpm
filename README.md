# Predicting BPM - Kaggle Competition

![Python](https://img.shields.io/badge/Python-3.&"%2B-blue?logo=python&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-Competition-20BEFF?logo=kaggle&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

A machine learning project for predicting the beats-per-minute (BPM) of songs using audio features. Part of Kaggle's Playground Series S5E9.

**Competition Link:** [Kaggle Playground Series S5E9](https://www.kaggle.com/competitions/playground-series-s5e9/overview)

## 📊 Project Overview

This competition involves predicting the BPM of songs from synthetically-generated audio features. The challenge is to build models that can accurately estimate tempo from various musical characteristics.

**Evaluation Metric:** Root Mean Squared Error (RMSE)

## 🎯 Key Insights

*To be updated as the project progresses*

- Data characteristics and patterns
- Important features for BPM prediction
- Model performance observations

## 📁 Repository Structure

```
kaggle-predicting-bpm/
│
├── data/                    # Data directory (not tracked in git)
│   └── kaggle/
│       ├── input/          # Competition data files
│       └── working/        # Kaggle working directory
│
├── notebooks/              # Jupyter notebooks for analysis
│   ├── 01_eda.ipynb       # Exploratory Data Analysis
│   ├── 02_baseline.ipynb  # Baseline models (Random Forest, XGBoost)
│   ├── 03_neural.ipynb    # Neural network approaches
│   └── 04_ensemble.ipynb  # Ensemble and stacking methods
│
└── README.md
```

## 🚀 Approaches

| Notebook | Model Type | Description | CV Score | LB Score |
|----------|------------|-------------|----------|----------|
| Baseline | Random Forest | Initial benchmark | - | - |
| Baseline | XGBoost | Gradient boosting approach | - | - |
| Neural | MLP | Multi-layer perceptron | - | - |
| Ensemble | Stacking | Combined predictions | - | - |

## 🛠️ Technologies Used

- **Python 3.x**
- **Data Processing:** pandas, numpy
- **Visualization:** matplotlib, seaborn
- **Machine Learning:** scikit-learn, xgboost, lightgbm
- **Deep Learning:** TensorFlow/Keras or PyTorch (if applicable)

## 📈 Results

*Final leaderboard position and score to be added upon competition completion*

## 📝 Citation

Walter Reade and Elizabeth Park. Predicting the Beats-per-Minute of Songs. https://kaggle.com/competitions/playground-series-s5e9, 2025. Kaggle.

