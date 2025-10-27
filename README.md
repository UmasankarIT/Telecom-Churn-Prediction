# 📊 Telecom Churn Prediction

This project focuses on predicting **customer churn in the telecom industry** using machine learning. It identifies which customers (or areas) are likely to leave the service, helping telecom providers take preventive actions.  

---

## 🎯 **Objective**
To analyze telecom subscriber data and build a predictive model that classifies whether a customer will **churn (leave)** or **stay**, based on factors like:
- Circle (Region/Area)
- Technology (2G, 3G, 4G, 5G)
- Service Provider
- Year and Month

---

## 🧩 **Dataset**
The dataset contains telecom subscriber information across multiple years, circles, and technologies.  
Key columns include:
- `year`
- `month`
- `circle`
- `technology`
- `service_provider`
- `value` (subscriber count)
- `churn` (Target variable: 0 = Not Churned, 1 = Churned)

---

## ⚙️ **Data Preprocessing**
- Cleaned missing and duplicate values  
- Converted categorical columns using **Label Encoding**  
- Split the data into **train** and **test** sets  
- Applied **feature importance** to identify the most impactful variables  

---

## 🤖 **Machine Learning Models**
Several ML algorithms were tested and compared based on accuracy:

| Model | Accuracy |
|--------|-----------|
| Logistic Regression | **0.9842** ✅ |
| Decision Tree | 0.9699 |
| Random Forest | 0.9638 |
| XGBoost | 0.9718 |
| K-Nearest Neighbors (KNN) | 0.9073 |
| Support Vector Machine (SVM) | 0.5982 |

🏆 **Best Model:** Logistic Regression (98.42%)

---

## 📈 **Churn Insights**
Performed **multi-variable analysis** to understand churn patterns:
- Churn by **circle (region)** and **technology**
- Churn trends across **years**
- High churn service providers

Example summary:
```text
Year | Circle | Technology | Not Churned | Churned | Churn Rate (%)
2023 | Mumbai | 5G | 22 | 26 | 54.16
2020 | Tamil Nadu | 4G | 33 | 39 | 54.16


🧑‍💻 Author
Umashankar G
mail - umashankargudivada@gmail.com

