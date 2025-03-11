# **PHASE_3_CAPSTONE**
---
# **README: Customer Churn Prediction & Analysis**
---
# **Project Overview**
---
This project aims to predict whether a telecommunications customer is at risk of soon stopping business with the company. Using machine learning classifiers, we identify customers likely to churn and provide actionable insights for customer retention.

**Key Features**

1. Exploratory Data Analysis (EDA) with visualizations to understand customer behavior.

2. Feature Engineering: Identifying important predictors of churn.

3. Machine Learning Models: Five models for classification.

4. Statistical Analysis: Hypothesis testing and correlation analysis.

5. Business Insights & Recommendations for Reducing Churn.



---

# **Dataset**
---
The data for this project was obtained from Kaggle's : **Churn in Telecom's dataset**

Columns: Includes usage statistics, customer service calls, and plan details.

Target Variable: soon_churn (1 = high risk of churn, 0 = likely to stay).



---

Exploratory Data Analysis (EDA) & Visualizations

1. Churn Distribution

**Customers with higher churn need special attention.**

![image](https://github.com/user-attachments/assets/4c297765-a0bd-452f-9f16-605568f73a53)


**Insight :**

The dataset has an imbalance (fewer churned customers).

Companies should focus more on churned customers.



---

2. Correlation Heatmap

Shows relationships between features and churn.
![image](https://github.com/user-attachments/assets/a4b872ee-d265-4c15-8b53-87e1fca6c88d)


**Insights :**

Customer service calls have the strongest positive correlation with churn.

Total call minutes and charges are also important factors.



---

3. Boxplots: Key Features vs. Churn

![image](https://github.com/user-attachments/assets/9613ead2-6d51-45ab-8ca7-e81dfadf2be9)


 **Insights :**

High total day minutes customers churn more.

More customer service calls indicate dissatisfaction.



---

Preprocessing & Feature Engineering

Dropped irrelevant columns (e.g., phone number).

One-hot encoded categorical features (state, international plan).

Created soon_churn as a new target variable.

Standardized numerical features for model training.



---

Machine Learning Models

We trained five classifiers and compared their accuracy:

![image](https://github.com/user-attachments/assets/86b28b15-7420-48a8-82b8-0519d98d6cb9)


Model Performance

 Best Models: XGBoost & Random Forest (Highest accuracy).


---

Statistical Analysis

SUMMARY OF STATISTICAL FINDINGS

1. Churned customers have significantly different call durations.
2. Customer service calls strongly impact churn.
3. Having an international plan is correlated to higher churn.

---

Business Solutions & Recommendations

 1. Proactive Customer Support

Reach out to customers with >3 customer service calls.

Provide better issue resolution & loyalty rewards.


 2. Personalized Retention Offers

Offer special discounts to at-risk customers.

Create flexible data/call plans based on usage.


 3. AI-Powered Chatbots for Customer Assistance

Deploy chatbots to handle common complaints.

Automate responses to prevent churn before it happens.


---


How to Run the Project

1. Install code editor/use Google Colab.

2. Run Jupyter Notebook

jupyter notebook churn_analysis.ipynb

3. Load Data & Train Models

Open churn_analysis.ipynb

Run all cells to train models and visualize results



---

Conclusion

By using EDA, statistical analysis, and machine learning, we:
* Identified key churn indicators.
* Built high-accuracy models (XGBoost, Random Forest).
* Provided actionable business insights for reducing churn.

