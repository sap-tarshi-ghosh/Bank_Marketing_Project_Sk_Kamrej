# 🚀 Bank Marketing Prediction Project

> 💡 A Machine Learning project to predict whether a customer will subscribe to a term deposit using advanced models, sampling techniques, and explainable AI.

---

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Objectives](#-objectives)
- [Project Structure](#-project-structure)
- [Technologies Used](#-technologies-used)
- [Workflow](#workflow)
  - [Data Preprocessing](#1-data-preprocessing)
  - [Handling Imbalanced Data](#2-handling-imbalanced-data)
  - [Model Building](#3-model-building)
  - [Model Evaluation](#4-model-evaluation)
- [Advanced Analysis](#-advanced-analysis)
- [Explainable AI](#-explainable-ai)
- [Key Results](#-key-results)
- [How to Run](#-how-to-run)
- [Use Cases](#-use-cases)
- [Future Improvements](#-future-improvements)
- [Contribution](#-contribution)
- [Contact](#-contact)
- [Support](#-support)

---

## 📌 Project Overview

This project focuses on solving a **real-world banking problem** — predicting customer responses to marketing campaigns.

Using **Machine Learning + Data Balancing + Explainable AI**, we build a powerful and interpretable model.

---

## 🎯 Objectives

- Predict whether a customer will subscribe (**Yes/No**)  
- Handle imbalanced data using advanced techniques  
- Compare multiple ML models  
- Apply statistical validation methods  
- Explain model decisions using AI interpretability tools  

---

## 📂 Project Structure

```bash
Bank_Marketing_Project/
│
├── Code/
│   ├── Bank_Marketing_Model.ipynb
│   ├── BMP_ADASYN.ipynb
│   └── ADASYN_SHAP_&_LIME.ipynb
│
├── Dataset/
│   ├── Bank_Marketing_Full.csv
│   └── Dataset_Info.md
│
├── Results/
│   ├── Bank_Marketing_Model_Results.xlsx
│   ├── BMP_ADASYN_ALL_Results.xlsx
│   ├── ADASYN_Friedman_Test_Results.xlsx
│   ├── ADASYN_TOPSIS_Ranking_Results.xlsx
│   └── ADASYN_Wilcoxon_Test_Results.xlsx
│
└── README.md
```

---

## 🧠 Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- ADASYN (Adaptive Synthetic Sampling)  
- Matplotlib, Seaborn  
- SHAP (Explainable AI)  
- LIME (Local Interpretability)  

---

## ⚙️ Workflow <a name="workflow"></a>

### 1. Data Preprocessing
- Handling missing values  
- Encoding categorical variables  
- Feature scaling  

### 2. Handling Imbalanced Data
- Applied **ADASYN (Adaptive Synthetic Sampling)**  

### 3. Model Building
- Logistic Regression  
- Random Forest  
- Gradient Boosting  
- Other ML models  

### 4. Model Evaluation

**Metrics used:**
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  
- MCC  
- G-Mean  
- Kappa  

---

## 📊 Advanced Analysis

### 🔢 TOPSIS Ranking
Used to rank models based on multiple evaluation metrics.

### 📉 Wilcoxon Test
Statistical test used to compare model performance.

---

## 🔍 Explainable AI

### SHAP
- Global feature importance  
- Understand model behavior  

### LIME
- Local prediction explanations  
- Instance-level interpretation  

---

## 📈 Key Results

- Improved model performance using ADASYN  
- Better ranking using TOPSIS  
- Statistically validated results using Wilcoxon test  
- Transparent predictions using SHAP & LIME  

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/Bank_Marketing_Project.git

# Navigate to project
cd Bank_Marketing_Project

# Install dependencies
pip install -r requirements.txt

# Run notebooks
jupyter notebook
```

---

## 📌 Use Cases

- 💼 Banking Marketing Strategy  
- 📢 Customer Targeting  
- 📊 Business Decision Support  
- 🤖 AI Model Explainability  

---

## 🌟 Future Improvements

- Deploy as a web app 🌐  
- Add real-time prediction system ⚡  
- Use Deep Learning models 🤖  
- Build dashboard (Power BI / Streamlit) 📊  

---

## 🤝 Contribution

Contributions are welcome!  
Feel free to fork, improve, and submit a pull request 🚀  

---

## 📧 Contact

📩 For queries or collaboration:  

- **Email:** skkamrej786@gmail.com  
- **GitHub:** https://github.com/Sk-Kamrej

**SK KAMREJ**  
📍 India  

---

## ⭐ Support

If you like this project:

- Give it a ⭐ on GitHub  
- Share with others

---

## 📝 Project Info

- **Last Updated:** April 25, 2026  
- **Repository:** [Sk-Kamrej/Bank_Marketing_Project](https://github.com/Sk-Kamrej/Bank_Marketing_Project)

---
