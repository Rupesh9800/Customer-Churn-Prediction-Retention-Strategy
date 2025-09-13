# Customer Churn Prediction & Retention Strategy  

## 📌 Overview  
This project focuses on analyzing customer churn in an e-commerce platform, identifying key factors that influence churn, and proposing actionable retention strategies.  
By leveraging data-driven insights, the goal is to improve customer satisfaction, reduce churn, and maximize revenue.

---

## 🎯 Objectives  
- Analyze patterns in customer behavior to identify churn drivers.  
- Build predictive models to estimate churn probability.  
- Propose strategies to improve retention and customer loyalty.  
- Visualize churn trends for better business understanding.  

---

## 📂 Dataset  
The dataset includes information about customers, their tenure, order amounts, city tiers, and satisfaction scores.  
Key features analyzed:  
- **Customer ID**  
- **Tenure**  
- **Estimated Monthly Spending**  
- **City Tier**  
- **Satisfaction Score**  
- **Churn Status**

---

## 📊 Key Insights  

### 📌 Overall Churn Percentage  
![Percentage of Customers who Left](images/Percentage%20of%20Customers%20who%20Left.png)

The churn rate is **16.84%**, meaning a significant portion of customers are leaving.  
This highlights the need for effective **retention strategies** to maintain revenue stability.  

---

### 1️⃣ Customer Churn by Tenure Range  
![Customer Churn by Tenure Range](images/Customer%20Churn%20by%20Tenure%20Range.png)

Customers with lower tenure have significantly higher churn rates.  
This indicates the importance of early engagement and onboarding programs.  

---

### 2️⃣ Average Estimated Monthly Spending by Tenure  
![Average Estimated Monthly Spending by Tenure](images/Average%20Estimated%20Monthly%20Spending%20by%20Tenure.png)

Spending patterns increase with tenure, meaning retaining long-term customers directly impacts revenue growth.  

---

### 3️⃣ Churn by Satisfaction Score  
![Churn by Satisfaction Score](images/Churn%20by%20Satisfaction%20Score.png)

Dissatisfied customers are much more likely to churn, highlighting the need for feedback systems and proactive support.  

---

### 4️⃣ Order Amount Hike by City Tier & Satisfaction  
![Order Amount Hike by City Tier and Satisfaction Score](images/Order%20Amount%20Hike%20by%20City%20Tier%20and%20Satisfaction%20Score.png)

Higher-tier cities and satisfied customers contribute more to order growth — these should be the primary focus of retention campaigns.  

---

## 🛠 Tech Stack  
- **Python** (Pandas, Matplotlib, Seaborn)  
- **Jupyter Notebook** for EDA & Visualization  
- **Machine Learning** (Logistic Regression, Decision Tree, Random Forest) for Churn Prediction  

---
## 📈 Model Performance  

| **Model**              | **Accuracy** | **Precision (Churn=1)** | **Recall (Churn=1)** | **F1 Score** |
|------------------------|-------------|------------------------|--------------------|-------------|
| Logistic Regression    | 0.89        | 0.72                  | 0.53              | 0.61        |
| Decision Tree          | 0.95        | 0.82                  | 0.87              | 0.84        |
| **Random Forest** ✅   | **0.97**    | **0.96**              | **0.84**          | **0.89**    |

**Key Takeaway:**  
✅ **Random Forest** selected as the final model for its **high accuracy (97%)** and **balanced recall (84%)**, ensuring better churn prediction with minimal false negatives.  

---

## 🏁 Conclusion  
- **Churn Prediction Success:** Achieved **97% model accuracy** with Random Forest.  
- **Key Finding:** Highest churn observed in the **first 18 months** — critical period for retention efforts.  
- **Customer Insights:** Satisfaction score and spending behavior are strong indicators of churn risk.  
- **Actionable Outcome:** Use churn predictions to **personalize engagement, improve onboarding, and design loyalty programs**.  
- **Business Impact:** Enables **proactive customer retention**, potentially reducing churn by double digits and increasing long-term revenue.  

---

## 🚀 Retention Strategy Recommendations  
- **Personalized Onboarding** for new customers (0–6 months tenure).  
- **Targeted Offers & Discounts** for medium-risk customers.  
- **Customer Support Enhancements** to improve satisfaction scores.  
- **City-Specific Campaigns** focusing on Tier 1 cities for higher ROI.  

---

## 📁 Project Structure  

```plaintext
📦 Customer Churn Prediction & Retention Strategy
 ┣ 📂 data/                               # Raw dataset
 ┣ 📂 images/                             # Visualization images
 ┣ 📜 Customer Churn Prediction & Retention Strategy.ipynb
 ┣ 📜 Customer_Churn_Presentation.pdf     # Final Presentation
 ┣ 📜 README.md                           # Project Documentation
 
