# 🏦 Bank Customer Churn Analysis & Prediction

## 📌 Project Overview

Customer retention is one of the most important challenges in the banking industry. Acquiring a new customer is significantly more expensive than retaining an existing one, making customer churn analysis a critical business function.

This project presents an end-to-end **Bank Customer Churn Analysis and Prediction System** that combines **Power BI, Python, Machine Learning, and a Web Application** to help identify customers at risk of leaving the bank.

The project is divided into three major components:

* **Interactive Power BI Dashboard** for business intelligence and customer behavior analysis.
* **Machine Learning Model** for predicting customer churn based on customer demographics and banking attributes.
* **Flask Web Application** that allows users to enter customer details and receive real-time churn predictions.

Rather than simply predicting whether a customer will churn, the project focuses on **understanding the business factors driving customer attrition and providing actionable insights that support strategic decision-making.**

---

# 📊 Customer Churn Analytics Dashboard

<img width="1506" height="800" alt="image" src="https://github.com/user-attachments/assets/2d118cff-ee89-4191-9643-74e96fe4755e" />


# 📈 Business Insights & Recommendations

## Overall Customer Churn Performance

The bank currently serves **10,000 customers**, of which **2,038 customers have churned**, resulting in an overall **churn rate of 20.38%**. This indicates that approximately **one out of every five customers leaves the bank**, representing a significant opportunity to improve customer retention and increase long-term profitability.

### Recommendation

* Prioritize customer retention initiatives as reducing churn by even a small percentage can generate substantial long-term revenue.

---

## Geographic Churn Analysis

Customer churn is concentrated primarily in **Germany and France**, while Spain contributes considerably fewer churn cases.

This indicates that customer attrition is influenced by regional factors rather than occurring uniformly across the customer base.

### Recommendation

* Perform branch-level performance analysis in Germany and France.
* Review customer feedback and service quality within these regions.
* Implement region-specific retention campaigns.

---

## Age-Based Customer Churn

The highest concentration of churn occurs among customers aged approximately **35–50 years**, with the peak occurring around the early to mid-40s.

This age group generally represents financially established customers with greater lifetime value, making their loss particularly costly.

### Recommendation

* Develop personalized banking offers for middle-aged customers.
* Strengthen relationship management and premium banking services.
* Improve customer engagement through tailored financial products.

---

## Gender Distribution of Churn

Female customers account for **55.89%** of total churn cases, while male customers represent **44.11%**.

Although the difference is moderate, it suggests an opportunity to further investigate customer expectations across different demographic groups.

### Recommendation

* Analyze customer feedback segmented by gender.
* Review whether existing banking products adequately meet customer needs.

---

## Customer Satisfaction Analysis

Customer satisfaction demonstrates one of the strongest relationships with customer retention.

Customers with satisfaction scores of **1 and 2** exhibit noticeably higher churn rates, whereas customers reporting higher satisfaction remain significantly more loyal.

### Recommendation

* Identify dissatisfied customers early.
* Improve complaint resolution time.
* Introduce loyalty rewards for highly satisfied customers.

---

## Customer Activity & Engagement

Inactive customers contribute disproportionately to customer churn despite maintaining average account balances similar to active customers.

This suggests that **customer engagement is a much stronger indicator of retention than account balance alone.**

### Recommendation

* Monitor inactive customers as an early warning signal.
* Launch personalized re-engagement campaigns.
* Encourage increased usage of digital banking services.

---

## Reward Points Analysis

Active customers consistently accumulate more reward points, while churned customers generally display lower reward engagement.

This suggests that loyalty programs positively influence long-term customer retention.

### Recommendation

* Expand reward-based engagement programs.
* Offer bonus points for consistent banking activity.
* Personalize reward campaigns according to customer behavior.

---

## Credit Score Analysis

Customers with **mid-range credit scores (approximately 600–700)** account for the largest share of churned customers.

Although customers with very high or very low credit scores exhibit fewer churn cases, the middle segment represents the greatest opportunity for retention due to its size.

### Recommendation

* Develop financial products specifically targeted at mid-credit customers.
* Provide financial advisory services and credit improvement programs.

---

## Customer Tenure Analysis

Average customer tenure remains close to **five years** across different credit score groups.

This indicates that tenure alone is not a strong determinant of churn, emphasizing that customer experience and engagement play a much larger role in retention.

### Recommendation

* Focus on continuous engagement throughout the customer lifecycle instead of relying solely on long customer relationships.

---

## Balance Analysis

Average account balances remain relatively similar between active and inactive customers.

This demonstrates that **account balance alone should not be considered a reliable predictor of customer loyalty.** Customer engagement, satisfaction, and banking activity provide significantly stronger indicators of future churn.

### Recommendation

* Combine financial metrics with behavioral indicators when identifying customers at risk of leaving.
* Build retention strategies based on engagement rather than balance alone.

---

# 🎯 Strategic Recommendations for Bank Management

Based on the dashboard analysis, the following initiatives are recommended:

* Prioritize retention strategies for customers aged **35–50 years**.
* Improve customer satisfaction through faster issue resolution and personalized service.
* Monitor inactive customers and intervene before churn occurs.
* Investigate the higher churn observed in **Germany and France**.
* Strengthen customer loyalty programs through reward-based incentives.
* Use predictive machine learning models to proactively identify high-risk customers and implement targeted retention campaigns before customer attrition occurs.

* # 🤖 Machine Learning Development

The predictive model was developed using **Python** in a Jupyter Notebook to identify customers who are likely to churn based on historical customer data.

The notebook follows a complete machine learning workflow, including:

* Data Collection
* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Categorical Encoding
* Model Training
* Model Evaluation
* Model Serialization using Joblib

The final trained model predicts whether a customer is likely to **Stay** or **Churn** by analyzing multiple customer attributes simultaneously, allowing the bank to proactively identify high-risk customers before they leave.

### 📓 Jupyter Notebook

The complete notebook containing all preprocessing, exploratory analysis, feature engineering, model training, and evaluation is available below.

**🔗 View Notebook:** https://github.com/aayushpatil834-hash/Bank-customer-churn-analysis-dashboard/blob/bb98d50d5380ff92edc18c801d94910e583f32c3/Churn_Customer_Bank.ipynb


---

# 🌐 Customer Churn Prediction Web Application

To make the predictive model accessible to business users, a **Flask-based web application** was developed.

The application allows relationship managers and bank employees to enter customer information through a simple interface and receive an instant churn prediction generated by the trained machine learning model.

This eliminates the need for technical knowledge while enabling faster, data-driven customer retention decisions.

---

## 🖥️ Web Application

### Home Page

📌 Scenario 1: Low Churn Risk (Likely to Stay)

<img width="1791" height="946" alt="image" src="https://github.com/user-attachments/assets/d2015fcd-34e7-4151-9df3-ca9da62c6b78" />

---

### Prediction Result

<img width="1800" height="898" alt="image" src="https://github.com/user-attachments/assets/845ab0ec-c803-4716-a1d4-43d6230b95c1" />

---

### Home Page

📌 Scenario 2: High Churn Risk

<img width="1780" height="892" alt="image" src="https://github.com/user-attachments/assets/18aec0f0-0600-4e2d-b507-282d385dcb1f" />

---

### Prediction Result

<img width="1775" height="882" alt="image" src="https://github.com/user-attachments/assets/32e0b7f7-0c16-4c28-b375-6d450ff4ad7b" />


### Home Page

📌 Scenario 3: Premium Customer

<img width="1755" height="885" alt="image" src="https://github.com/user-attachments/assets/72fc887f-e304-477b-872f-0c45d920ca81" />

---

### Prediction Result

<img width="1797" height="841" alt="image" src="https://github.com/user-attachments/assets/ee8c0266-0c59-46b8-acd5-22a9e3ebd3d8" />


---

## Key Features

* Real-time customer churn prediction
* User-friendly interface
* Machine Learning model integration
* Instant prediction results
* Responsive web application
* Simple customer input form
* Business-friendly decision support

---

## Business Value

The web application converts the trained machine learning model into a practical decision-support tool for banking professionals.

It enables the bank to:

* Identify high-risk customers before they churn.
* Support customer relationship managers with predictive insights.
* Deliver personalized retention campaigns.
* Improve customer satisfaction through timely intervention.
* Reduce customer acquisition costs by increasing retention.

---

# 🛠️ Technologies Used

| Category                | Technologies              |
| ----------------------- | ------------------------- |
| Programming Language    | Python                    |
| Data Analysis           | Pandas, NumPy             |
| Data Visualization      | Matplotlib, Power BI      |
| Machine Learning        | Scikit-learn              |
| Model Storage           | Joblib                    |
| Web Framework           | Flask                     |
| Frontend                | HTML, CSS, Bootstrap      |
| Development Environment | Jupyter Notebook, VS Code |

---

# 📂 Project Structure

```text
Bank-Customer-Churn-Analysis/
│
├── dashboard/
│   ├── Bank_Churn_Dashboard.pbix
│   └── dashboard.png
│
├── notebook/
│   └── Bank_Customer_Churn_Analysis.ipynb
│
├── model/
│   ├── churn_model.pkl
│   └── columns.json
│
├── web_app/
│   ├── app.py
│   ├── templates/
│   ├── static/
│   └── requirements.txt
│
├── dataset/
│   └── Churn_Modelling.csv
│
└── README.md
```

