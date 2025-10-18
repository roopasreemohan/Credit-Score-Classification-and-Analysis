# 💳 Credit Score Classification using Machine Learning & Plotly

### 🧠 Predicting Customer Creditworthiness with Explainable Insights

This project analyzes and predicts **credit scores (Good / Standard / Poor)** using machine learning models and **interactive visualizations**.  
It leverages the [Credit Score Classification Dataset by ParisRohan](https://www.kaggle.com/datasets/parisrohan/credit-score-classification) from Kaggle.

---

## 📁 Dataset Overview

The dataset contains customer demographic and financial information.

## ⚙️ Tech Stack

- 🐍 **Python 3**
- 📊 **Pandas**, **NumPy** — Data preprocessing & analysis  
- ⚡ **Scikit-learn** — Machine learning (RandomForest, feature importance)  
- 📈 **Plotly Express**, **Plotly Graph Objects**, **Plotly IO** — Interactive visualizations  
- 🎨 **Plotly Templates** — Consistent styling for all charts

## 🚀 Project Workflow

### 1️⃣ Data Preprocessing
- Handle missing values  
- Encode categorical variables using `LabelEncoder`  
- Scale numerical features using `StandardScaler`  

### 2️⃣ Model Training
- Split dataset into training and test sets (80/20)
- Train a **Random Forest Classifier**
- Evaluate using:
  - Classification Report  
  - Confusion Matrix  
  - Feature Importance Visualization  

### 3️⃣ Interactive Visual Analysis (Plotly)
- Occupation vs Credit Score (Histogram)
- Annual Income vs Credit Score (Box Plot)
- Number of Bank Accounts vs Credit Score (Box Plot)
- Outstanding Debt & Delay vs Credit Score
- Correlation Heatmap

## 📊 Key Insights

- **Income and Debt Levels** strongly influence credit scores.  
- **Payment behavior** and **credit utilization ratio** have significant predictive power.  
- Customers with **moderate bank accounts and low delays** tend to have higher credit scores.  
- Random Forest achieved a **high accuracy (80–90%)** on test data.

---

## 🧩 Visualizations Preview

| Plot | Description |
|------|--------------|
| 🟦 Feature Importance | Highlights which factors most affect credit scores |
| 💰 Income vs Score | Boxplot showing income variation across credit score classes |
| 🏦 Bank Accounts vs Score | Relationship between number of accounts and creditworthiness |
| 🔥 Correlation Heatmap | Shows inter-feature relationships and dependencies |

---

## 🧮 Model Evaluation

| Metric | Value (approx.) |
|--------|-----------------|
| Accuracy | ~0.85 |
| Precision | 0.83 |
| Recall | 0.82 |
| F1 Score | 0.83 |

---
📁 Credit-Score-Classification/
│
├── 📄 README.md → Project documentation + Visualizations screenshots
├── 📊 credit_score.py → Full code (EDA + ML + Visualizations)

##Classification Report

<img width="429" height="226" alt="image" src="https://github.com/user-attachments/assets/b1b0df93-89f2-4b4d-9869-c7c04658dd75" />


##Confusion Matrix - Actual vs Predicted

<img width="1251" height="345" alt="image" src="https://github.com/user-attachments/assets/00227572-0fa0-40bb-9afc-7315a8f0f998" />


##BAR graph on Feature Importance

<img width="1168" height="340" alt="image" src="https://github.com/user-attachments/assets/1afefa71-aaae-4deb-bb9f-7e381a3ec1ad" />


##HISTOGRAM - Occupation Vs Credit Score

<img width="1257" height="346" alt="image" src="https://github.com/user-attachments/assets/279f8402-c31d-49d7-b79d-e5ade77d62db" />


##BOX Plot - Annual Income vs Credit Score

<img width="1250" height="358" alt="image" src="https://github.com/user-attachments/assets/1b16c34e-9c06-480f-9e96-63e02a38d8c1" />

##BOX Plot - Number of Bank Accounts Vs Credit Score

<img width="1254" height="341" alt="image" src="https://github.com/user-attachments/assets/2f54ad45-3624-44ba-840d-3050931004d3" />


##Correlation Heatmap

<img width="1238" height="356" alt="image" src="https://github.com/user-attachments/assets/76303c04-bf8c-44ed-af50-a1f7d302e5e5" />




