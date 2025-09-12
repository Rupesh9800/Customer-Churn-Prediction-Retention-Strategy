# 📊 Customer Churn Prediction & Retention Strategy  

## 📌 Overview  
This project performs a **comprehensive churn analysis** for an e-commerce business, aiming to identify key factors driving customer attrition and predict which customers are at risk of leaving. Using **EDA, feature engineering, and machine learning models**, the analysis delivers actionable insights for improving customer retention and business growth.  

---

## 🎯 Objectives  
- Identify **patterns and reasons** behind customer churn  
- Analyze customer behavior based on demographics, tenure, spending, and satisfaction  
- Build machine learning models to **predict churn probability**  
- Recommend **targeted retention strategies** based on data insights  

---

## 📂 Dataset  
- **Entries:** 5,630 customers  
- **Features:** 20 columns including tenure, preferred payment mode, satisfaction score, complaint history, spending behavior, and churn status  
- **Key Stats:**  
  - ~16.84% churn rate  
  - Missing values handled with **KNN Imputer**  
  - Encoded categorical variables using **One-Hot Encoding**  

---

## 🔧 Tools & Libraries  
- **Language:** Python  
- **Data Handling:** pandas, numpy  
- **Visualization:** matplotlib, seaborn  
- **Machine Learning:** scikit-learn (Logistic Regression, Decision Tree, Random Forest)  
- **Metrics:** Accuracy, Precision, Recall, F1-score, Confusion Matrix  

---

## 📊 Exploratory Data Analysis (EDA)  

### 🔍 Key Findings  
- **Churn Rate:** ~16.84% of customers left the service  
- **Tenure Impact:** High churn observed in the **first 18 months** – onboarding experience is crucial  
- **Gender Differences:** Male customers show slightly higher churn → need gender-targeted engagement strategies  
- **Satisfaction Link:** Higher satisfaction scores strongly correlate with lower churn  
- **Spending Behavior:**  
  - New customers show high spending variability → need early engagement  
  - Spending drops around 30 months, indicating potential mid-tenure disengagement  

---

## 📸 Key Visualizations  

### Average Monthly Spending by Tenure  
![Average Estimated Monthly Spending by Tenure](images/Average%20Estimated%20Monthly%20Spending%20by%20Tenure.png)

### Churn by Satisfaction Score  
![Churn by Satisfaction Score](images/Churn%20by%20Satisfaction%20Score.png)

### Churn by Tenure Range  
![Customer Churn by Tenure Range](images/Customer%20Churn%20by%20Tenure%20Range.png)

### Order Amount Hike by City Tier & Satisfaction Score  
![Order Amount Hike by City Tier and Satisfaction Score](images/Order%20Amount%20Hike%20by%20City%20Tier%20and%20Satisfaction%20Score.png)

---

## 🤖 Model Development  
- **Algorithms Used:**  
  - Logistic Regression  
  - Decision Tree Classifier  
  - Random Forest Classifier (best performing)  
- **Outcome:** Identified **923 high-risk customers** likely to churn  

---

## 💡 Recommendations  
- **Early Engagement:** Improve onboarding and offer early incentives to reduce first-18-month churn  
- **Customer Feedback:** Actively collect and act on feedback from customers who leave early  
- **Targeted Offers:** Personalize discounts and offers for high-risk segments (short tenure + high spending)  
- **Loyalty Programs:** Reward long-term customers to sustain engagement  
- **Demographic-Specific Interventions:** Focus on senior citizens and customers without partners/dependents  
- **Service Optimization:** Bundle services or offer flexible plans to improve satisfaction  

---

## 🚀 Future Scope  
- Deploy a **churn prediction dashboard** for real-time monitoring  
- Use advanced models like **XGBoost / LightGBM** for higher accuracy  
- Integrate customer feedback text analysis (NLP) for richer insights  

---

## 🖥️ How to Run  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Rupesh9800/customer-churn-prediction.git
   cd customer-churn-prediction

## 👤 Author
Rupesh Varma
📧 rupeshvarma6296@gmail.com
🔗 LinkedIn
