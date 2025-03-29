# Customer Churn Analysis

## Problem Statement

This analysis aims to help businesses understand customer churn patterns and identify key factors influencing customer retention. By analyzing customer demographics, behavior, and subscription details, businesses can implement targeted strategies to reduce churn and improve customer satisfaction.

## Dataset Overview

The dataset contains customer information, including:
- **Customer ID**
- **Demographics** (Gender, Age, Location)
- **Subscription Details** (Tenure, Plan Type, Monthly Charges, Total Charges)
- **Usage Metrics** (Internet Service, Streaming Services, Call Services)
- **Churn Label** (Whether the customer has left or stayed)

![Image](https://github.com/user-attachments/assets/502855fe-821d-4023-9013-a8f1cd3e3523)

### Key Insights from the Analysis

1. **Churn Rate**: The overall churn rate in the dataset is **26.5%**, meaning that about **1 in 4 customers** has left the service.
2. **Monthly Charges Impact**: Customers with higher monthly charges (> $70) have a churn rate of **42.3%**, significantly higher than customers with lower monthly charges.
3. **Tenure Influence**: Customers with a tenure of less than 12 months have a churn rate of **58.1%**, indicating that new customers are more likely to leave.
4. **Service Impact**:
   - Customers without internet service have a churn rate of only **8.3%**, while those with fiber-optic internet churn at **41.5%**.
   - Customers who subscribe to streaming services have a **10% lower churn rate** compared to those who don’t.
5. **Contract Type**:
   - Month-to-month customers have the highest churn rate at **60.2%**.
   - Customers with 2-year contracts churn at only **4.1%**.
6. **Payment Method**:
   - Customers using electronic checks churn at **44.5%**, while credit card and bank transfer users churn at **10.2%**.

## Visualizations

![Image](https://github.com/user-attachments/assets/e4b4a8f0-9296-4e69-a716-17eb43761fc0)

### Churn Distribution

![Image](https://github.com/user-attachments/assets/96cb350d-d2f5-4e69-a61e-d6b6af4d9eaa)

### Contract Type and Churn

![Image](https://github.com/user-attachments/assets/9ce0fb03-113b-4bb9-9c9c-377084cd7132)

## Steps Followed in the Analysis

### 1. Data Cleaning & Preprocessing
- Removed null values and missing data.
- Converted categorical variables into numerical representations.
- Standardized numerical features for better model performance.



### 2. Exploratory Data Analysis (EDA)
- Visualized churn distribution using bar charts and pie charts.
- Examined relationships between churn and key variables using heatmaps and correlation matrices.
- Identified high-risk customer segments based on tenure, contract type, and monthly charges.

### 3. Model Building
- Used logistic regression, decision trees, and random forests to predict churn.
- Evaluated models using accuracy, precision, recall, and F1-score.

### 4. Key Recommendations
- Encourage customers to switch from **monthly contracts** to **long-term contracts** to reduce churn.
- Offer **discounts or loyalty rewards** for customers in the first year to improve retention.
- Improve customer experience for **fiber-optic users**, as they have the highest churn rate.
- Introduce incentives for customers using **electronic checks** to switch to more stable payment methods.

## Tools & Technologies Used
- **Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)**
- **Jupyter Notebook**
- **Machine Learning Models (Logistic Regression, Decision Trees, Random Forests)**

## Future Improvements
- Incorporate additional customer feedback data to understand reasons behind churn.
- Apply deep learning models for better churn prediction.
- Conduct A/B testing on retention strategies to measure effectiveness.

---

Feel free to clone this repository and explore the notebook for further insights. Contributions and feedback are welcome!
