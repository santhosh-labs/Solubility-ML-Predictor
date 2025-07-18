# 🧪 Solubility Prediction using Machine Learning

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

## 🗃️ Project Structure

- `notebooks/` – Colab/Jupyter notebook
- `models/` – Trained model (`Random-Forest-Regressor-Model.pkl`)
- `data/` – Dataset file (`Dataset_solubility.csv`)

## 📦 How to Run

Clone the repository and open the notebook:
```bash
