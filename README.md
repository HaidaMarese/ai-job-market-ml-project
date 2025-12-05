# AI Job Market ML Project  
### *Predicting Increasing vs. Decreasing Jobs (2024–2030)*

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

---

##  Overview

This repository contains my final project for **ITCS 3156 – Machine Learning** at UNC Charlotte.

The goal of this project is to **predict whether a job is increasing or decreasing from 2024–2030** using supervised machine learning models such as:

- **Logistic Regression**
- **Random Forest Classifier**

The dataset includes **30,000+ job records** with multiple economic, demographic, and occupational features.

The project follows a complete machine learning pipeline:

- Data exploration  
- Visual analysis  
- Preprocessing (cleaning, encoding, scaling, splitting)  
- Training ML models  
- Evaluating results  
- Comparing model performance  
- Feature importance interpretation  

---


##  Project Workflow

The machine learning pipeline includes:

### **1. Data Exploration**
- Dataset introduction  
- Checking class balance  
- Visualizing feature distributions  
- Correlation heatmaps  

### **2. Preprocessing**
- Cleaning missing values  
- One-hot encoding categorical features  
- Scaling numeric features  
- Train/test split  

### **3. Machine Learning Models**
Two models were trained and evaluated:

- **Logistic Regression**  
- **Random Forest Classifier**

Both models were implemented using **scikit-learn**.

### **4. Evaluation Metrics**
Performance was analyzed using:

- Accuracy  
- F1-Score  
- Confusion Matrix  
- Feature importances (Random Forest)

---

##  Key Results

- Logistic Regression provided interpretable linear decision boundaries.
- Random Forest captured nonlinear relationships and performed strongly on feature importance analysis.
- Model comparison shows differences in how each algorithm handles complex, high-dimensional job market data.

---

## How to Run the Notebook

###  Clone the repository
```bash
git clone https://github.com/HaidaMarese/ai-job-market-ml-project.git
cd ai-job-market-ml-project
```
## Install dependencies
pip install -r requirements.txt

## Launch the notebook
jupyter notebook final_project_ai_job_market.ipynb

## Acknowledgement

I reused portions of my previous coursework from ITCS 3156, specifically:

- Module 2 – Machine Learning Basics

- Module 8 – Logistic Regression

- Module 9 – Random Forest


## References (MLA Style)

Dataset
Islam, Sahil. “AI Impact on Job Market: Increasing vs. Decreasing Jobs (2024–2030).” Kaggle, 2025,
https://www.kaggle.com/datasets/sahilislam007/ai-impact-on-job-market-20242030

Resources
Scikit-learn Developers. “sklearn.linear_model.LogisticRegression—scikit-learn documentation.”
https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html

Scikit-learn Developers. “sklearn.ensemble.RandomForestClassifier—scikit-learn documentation.”
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html

Scikit-learn Developers. “sklearn.compose.ColumnTransformer — scikit-learn documentation.”
https://scikit-learn.org/stable/modules/generated/sklearn.compose.ColumnTransformer.html

Pandas Development Team. “pandas.DataFrame — pandas documentation.”
https://pandas.pydata.org/docs/reference/frame.html

Waskom, Michael. “Seaborn: Statistical Data Visualization.”
https://seaborn.pydata.org/

Course Materials – ITCS 3156: Introduction to Machine Learning, UNC Charlotte.

##  License

Distributed under the MIT License.
You may use this project for academic or personal learning purposes.




