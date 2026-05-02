# 🌍 Global Terrorism Analysis  
### *EDA • Hypothesis Testing • Machine Learning*

---

## 📌 Overview

This project presents a comprehensive analysis of the **Global Terrorism Dataset (1970–2017)**, containing over **181,000 recorded incidents** worldwide. The objective is to transform raw data into **actionable insights** using:

- 📊 Exploratory Data Analysis (EDA)  
- 🧪 Statistical Hypothesis Testing  
- 🤖 Machine Learning Models  

---

## 🎯 Key Objectives

- Clean and preprocess real-world large-scale data  
- Explore temporal, geographical, and operational patterns  
- Validate insights using statistical hypothesis testing  
- Build classification models to predict attack success  
- Generate insights useful for policy and decision-making  

---

## 📂 Dataset

- **Source:** Global Terrorism Database (GTD)  
- **Time Range:** 1970–2017  
- **Records:** 181,000+ incidents  

---

## 🧼 Data Preprocessing

- Removed duplicates and irrelevant columns  
- Handled missing values:
  - `"Unknown"` for categorical variables  
  - `0` for numerical variables  
- Created new feature:
  - `casualties = nkill + nwound`  
- Retained outliers due to real-world significance  

---

## 📊 Exploratory Data Analysis

- 📈 Year-wise attack trends  
- 🌍 Region & country distribution  
- 💣 Attack type analysis  
- 🎯 Target type analysis  
- ☠️ Casualty distribution  
- 🔥 Correlation analysis  

---

## 📉 Visualizations

- Line charts (time trends)  
- Bar charts (countries, attack types)  
- Pie/Donut charts (distributions)  
- Histogram (casualties)  
- Boxplot (outliers)  
- Heatmap (correlations)  

---

## 🧪 Hypothesis Testing

- **T-Test:** Casualties vs Attack Success  
- **Chi-Square Test:** Weapon Type vs Success  
- **Correlation Test:** Killed vs Wounded  

✔ Confirms insights are statistically significant  

---

## 🤖 Machine Learning

### Models Used:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- KNN  
- Gradient Boosting  
- Naive Bayes  

### Metrics:
- Accuracy  
- Precision  
- Recall  
- F1 Score  

### Result:
- Random Forest & Gradient Boosting performed best  

---

## 💡 Key Insights

- Terrorism is concentrated in specific regions  
- Bombings & armed assaults are most common  
- Few groups account for majority of attacks  
- Casualties are highly skewed  
- Attack success depends on multiple factors  

---

## 👥 Business Impact

- Supports policy-making & security planning  
- Helps identify high-risk regions  
- Improves resource allocation  
- Assists in emergency preparedness  

---

## ✍️ Author

**Anshika Thapliyal**
