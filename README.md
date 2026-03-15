# 🏥 Healthcare Readmission Prediction

> End-to-end ML pipeline predicting 30-day hospital readmissions for diabetes patients using Python.

---

## 📌 Project Overview

| Detail | Info |
|---|---|
| **Dataset** | Diabetes 130-US Hospitals (1999–2008), UCI ML Repository |
| **Records** | 101,766 hospital admissions |
| **Target** | 30-day readmission (binary classification) |
| **Best Model** | Random Forest (AUC: 0.65, Accuracy: 75.54%) |

---

## 🔍 Key Findings

- **Readmission rate**: 11.16% (11,357 out of 101,766 patients)
- **Top risk factors**: Prior inpatient admissions, ED utilization, age 70+, circulatory/respiratory diagnoses
- **Risk stratification**:
  - 🟢 Low Risk: 4.9% readmission rate
  - 🟡 Medium Risk: 9.8% readmission rate
  - 🔴 High Risk: 18.1% readmission rate
  - 🚨 Very High Risk: 41.5% readmission rate

---

## 📊 Model Performance

| Metric | Score |
|---|---|
| Accuracy | 75.54% |
| Precision | 19.49% |
| Recall | 38.09% |
| F1 Score | 25.79% |
| ROC AUC | 0.6529 |

---

## 💰 Business Impact (Hypothetical)

- Patients flagged for intervention: **4,438**
- Estimated readmissions prevented: **606**
- Potential net savings: **$4,644,500**

---

## 📁 Project Structure
```
healthcare-readmission-prediction/
├── Healthcare_Analytics.ipynb    # Main analysis notebook
├── diabetic_data_cleaned.csv     # Preprocessed dataset
├── EXECUTIVE_SUMMARY.txt         # Executive summary report
├── requirements.txt              # Python dependencies
├── README.md                     # This file
└── visualizations/               # All generated charts
    ├── 01_target_distribution.png
    ├── 02_numeric_distributions.png
    ├── 03_categorical_distributions.png
    ├── 04_numeric_vs_readmission.png
    ├── 05_categorical_vs_readmission.png
    ├── 06_correlation_matrix.png
    ├── 07_model_comparison.png
    ├── 08_confusion_matrices.png
    ├── 09_feature_importance.png
    ├── 10_probability_distribution.png
    ├── 11_risk_stratification.png
    └── 12_FINAL_DASHBOARD.png
```

---

## ⚙️ How to Run

1. Download `diabetic_data.csv` from [UCI ML Repository](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008)
2. Place it in the project root directory
3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Open and run the notebook:
```bash
jupyter notebook Healthcare_Analytics.ipynb
```

---

## 🛠️ Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 👤 Author

**Mayank Choudhary**
MS Data Science | Stevens Institute of Technology

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mayankchoudhary23/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:mayankchoudharystevens909@gmail.com)
