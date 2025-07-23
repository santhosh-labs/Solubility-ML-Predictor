# 🧪 Solubility Prediction using Machine Learning
![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![ML Model](https://img.shields.io/badge/Model-Random%20Forest-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)


This project aims to predict the aqueous solubility (logS) of chemical compounds based on molecular descriptors. Solubility is a critical property in drug discovery and formulation, influencing a molecule’s bioavailability and absorption. We use machine learning techniques to build regression models that can estimate logS from easily computable molecular features.

## 🔬 Dataset

The dataset includes 1,144 molecules with the following features:
- `MolLogP`: Octanol-water partition coefficient
- `MolWt`: Molecular weight
- `NumRotatableBonds`
- `AromaticProportion`
- **Target**: `logS` (logarithmic solubility)

## ⚙️ Models Used

- **Linear Regression** (Baseline model)
- **Random Forest Regressor** (Improved model)

## 📈 Results

| Metric     | Linear Regression | Random Forest |
|------------|-------------------|---------------|
| Train R²   | 0.7645            | 0.9798        |
| Test R²    | 0.7892            | 0.8658        |
| Test MSE   | 1.0207            | 0.6495        |

✅ The Random Forest Regressor demonstrated significantly better accuracy and generalization.




## 🚀 Clone This Repository

```bash
git clone https://github.com/santhosh-labs/Solubility-ML-Predictor.git
```
---
## 👤 Author

Santhosh S — Data Analyst, Focused on deriving actionable insights, simplifying complex data challenges, and delivering data-driven solutions across domains.

💼 LinkedIn: [Santhosh S](https://www.linkedin.com/in/santhosh-portfolio)  
- Let’s connect professionally and grow your data career


