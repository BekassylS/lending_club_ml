# lending_club_ml
# 💳 Lending Club Client Analysis Using Machine Learning

This project is a machine learning and data analysis study based on a real-world dataset from **Lending Club**, a peer-to-peer lending platform. The dataset includes detailed information about individual loan applicants such as their income, employment status, loan amount, loan status, and more.

The goal of the project is to explore which factors are most influential in predicting loan defaults and to compare different models in terms of accuracy and interpretability.

This work was part of my final project in a data analysis course during my economics studies.

---

## 📁 Project Files

- `LC_project_final.ipynb`: Main Jupyter Notebook where all data preprocessing, modeling, and evaluation are performed.
- `cleaned_lending_club_data.csv.zip`: Cleaned version of the dataset used for modeling im compressed format.
- `summary.md`: A plain-language summary of what was done, what worked, what didn’t, and key insights from the analysis. *(To be added)*

---

## 🛠️ Methods & Tools

### 🧹 Preprocessing
- Outlier detection and removal (e.g., via z-scores on income)
- Correlation analysis and feature selection
- Missing value handling and sampling due to dataset size

### 📊 Models Used
- **Logistic Regression** (with feature selection using `SequentialFeatureSelector`)
- **Linear Discriminant Analysis (LDA)**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Random Forest Regressor**
- **Linear Regression**

### 📚 Libraries
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`, `statsmodels`

---

## 🎯 Goals

- Identify important predictors of loan default
- Compare multiple classification models
- Assess trade-offs between accuracy and interpretability
- Practice model selection (e.g., forward/backward feature selection)

---

## 📌 Next Steps

- Add further EDA visualizations
- Finalize evaluation with precision/recall/F1 analysis
- Summarize conclusions and potential business implications in `summary.md`

---

## 🔍 Dataset Context

The Lending Club dataset is widely used in the data science community to model credit risk. It includes:
- Demographic information
- Financial variables (income, loan amount, interest rate)
- Target variable: loan status (fully paid vs charged off)

The original dataset can be found on [Kaggle](https://www.kaggle.com/datasets) or directly from Lending Club's official data portal.

---

Let me know if you'd like a version in Russian, more technical details, or edits once your summary is ready! ✅
