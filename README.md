# 🧬 ML for Bioinformatics — Obesity Classification & Regression

A machine learning project analyzing an obesity dataset to classify individuals into obesity levels and predict obesity scores using various ML models. This project was completed as part of a **Machine Learning for Bioinformatics** course.

---

## 📁 Project Structure

| Notebook | Description |
|----------|-------------|
| `01_KNN_from_scratch.ipynb` | Custom KNN implementation from scratch for obesity classification |
| `02_classification_models.ipynb` | Classification using KNN, Random Forest, and SVM |
| `03_regression_models.ipynb` | Regression using Multiple Linear Regression and SVR |
| `obesity.csv` | Dataset used across all notebooks |

---

## 📊 Dataset

The dataset contains health and lifestyle attributes used to classify individuals into obesity levels.

**Features include:** age, weight, height, family history, eating habits, physical activity, and more.

**Target variable:** `NObeyesdad` — obesity level category

---

## 🤖 Models Implemented

### Assignment 1 — KNN from Scratch
- Custom KNN classifier supporting Euclidean and Manhattan distance
- Grid search for hyperparameter tuning (k, distance metric)
- Cross-validation, confusion matrix, ROC & AUC analysis

### Assignment 2 — Classification Models
- **KNN** (custom implementation with hyperparameter tuning)
- **Random Forest** (tuned with RandomizedSearchCV)
- **Support Vector Machine** (tuned with Genetic Algorithm)
- Model comparison and best model deployment using Pickle
| Model | Accuracy | F1-Score |
|-------|----------|----------|
| KNN (from scratch) | ~85% | ~0.85 |
| Random Forest | **94.8%** | **0.948** |
| SVM (Genetic Algorithm) | 88.5% | 0.886 |

### Assignment 3 — Regression Models
- **Multiple Linear Regression** — baseline model with residual analysis
- **Support Vector Regression (SVR)** — tuned with GridSearchCV
- Model comparison using MSE, RMSE, and R² metrics
| Model | R² | RMSE |
|-------|-----|------|
| Multiple Linear Regression | 0.29 | — |
| Support Vector Regression | **0.67** | — |

---

## ⚙️ Data Preprocessing Pipeline

All notebooks follow the same preprocessing pipeline:
1. Load dataset and exploratory analysis
2. Handle missing values
3. Label encode categorical features
4. 70/30 train-test split
5. Min-Max normalization

---

## 📈 Visualizations

- Correlation heatmaps
- Boxplots per feature
- ROC & AUC curves (multi-class)
- Feature importance analysis
- Residual analysis plots

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat&logo=python&logoColor=white)


## 👩‍💻 Author

**Maria Rooeintan** — Biomedical Informatics Student @ University of Sharjah  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maria-taleb-64058a371/)
