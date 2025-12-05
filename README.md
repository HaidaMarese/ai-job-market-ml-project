# AI Job Market ML Project  
### Predicting Increasing vs. Decreasing Jobs (2024–2030)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

---

##  Overview  
This repository contains my final project for **ITCS 3156 – Machine Learning** at **UNC Charlotte**.

The goal of this project is to **predict whether a job is increasing or decreasing between 2024–2030** using supervised machine learning models:

- **Logistic Regression**
- **Random Forest Classifier**

The dataset includes **30,000+ job records** with economic, demographic, and occupational features.

The project follows a complete and professional **machine learning pipeline**, including:

- Data exploration  
- Visual analysis  
- Preprocessing (cleaning, encoding, scaling, splitting)  
- Model training  
- Evaluation  
- Model comparison  
- Feature importance interpretation  

---

##  Project Workflow  

### **1. Data Exploration**
- Overview of dataset  
- Checking class balance  
- Feature distribution visualizations  
- Correlation heatmaps  

### **2. Preprocessing**
- Handling missing values  
- One-hot encoding categorical variables  
- Scaling numeric features  
- Train/validation/test split  

### **3. Machine Learning Models**
Two models were implemented using **scikit-learn**:

- **Logistic Regression**
- **Random Forest Classifier**

### **4. Evaluation Metrics**
Model performance was assessed using:

- Accuracy  
- F1-Score  
- Confusion Matrix  
- Feature Importance (Random Forest)  

---

##  Key Results
- **Logistic Regression** provided interpretable linear decision boundaries.  
- **Random Forest** captured non-linear relationships and highlighted feature importance trends.  
- Both models struggled to generalize, revealing that job market growth/decline patterns are **complex and noisy**, requiring richer features.

---

## How to Run the Notebook

### **1. Clone the repository**
```bash
git clone https://github.com/HaidaMarese/ai-job-market-ml-project.git
cd ai-job-market-ml-project
```
##  Acknowledgement

I reused portions of my previous coursework from ITCS 3156, specifically:

. Module 2 – Machine Learning Basics

. Module 8 – Logistic Regression

. Module 9 – Random Forest


## References

Dataset
Islam, Sahil. “AI Impact on Job Market: Increasing vs. Decreasing Jobs (2024–2030).” Kaggle, 2025.
https://www.kaggle.com/datasets/sahilislam007/ai-impact-on-job-market-20242030

Resources
Scikit-learn Developers. “sklearn.linear_model.LogisticRegression — scikit-learn documentation.”
https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html

Scikit-learn Developers. “sklearn.ensemble.RandomForestClassifier — scikit-learn documentation.”
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html

Scikit-learn Developers. “sklearn.compose.ColumnTransformer — scikit-learn documentation.”
https://scikit-learn.org/stable/modules/generated/sklearn.compose.ColumnTransformer.html

Pandas Development Team. “pandas.DataFrame — pandas documentation.”
https://pandas.pydata.org/docs/reference/frame.html

Waskom, Michael. “Seaborn: Statistical Data Visualization.”
https://seaborn.pydata.org/

ITCS 3156: Introduction to Machine Learning. UNC Charlotte, 2025.

##  License
Distributed under the MIT License.
This project may be used for academic or personal learning purposes.

## Author
Haida Makouangou
Computer Science – AI, Robotics & Gaming Concentration
University of North Carolina at Charlotte

