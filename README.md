
---

## Bank Customer Churn Prediction

### Overview

This project focuses on predicting customer churn in a bank using machine learning techniques. Customer churn, or attrition, is a critical concern for businesses, including banks, as retaining existing customers is often more cost-effective than acquiring new ones. The goal of this project is to develop a predictive model that can identify customers who are at risk of leaving the bank, allowing the institution to take proactive measures to retain valuable clientele.

### Key Steps

1. **Data Exploration and Preprocessing**: The project begins with a thorough exploration of the dataset, which includes customer information such as credit score, age, balance, and more. Data preprocessing is performed to handle missing values and encode categorical variables.

2. **Exploratory Data Analysis (EDA)**: Visualizations are used to gain insights into relationships between various features and customer churn. EDA helps in uncovering patterns and trends that can inform the modeling process.

3. **Feature Engineering**: New features are created to potentially capture additional information and improve model performance. For example, features like `BalanceSalaryRatio` and `CreditScoreGivenAge` are introduced.

4. **Model Building and Evaluation**: Several machine learning models are employed, including Logistic Regression, Decision Tree Classifier, Random Forest Classifier, and XGBoost Classifier. The models are evaluated using a range of metrics, such as accuracy, ROC AUC score, recall, precision, and F1 score.

5. **Hyperparameter Tuning**: Grid Search is used to fine-tune hyperparameters, optimizing the model's performance.

6. **Model Deployment**: The best-performing model is selected and can be deployed to make predictions on new data.

### Results

The project's highlight is the XGBoost Classifier, which achieved impressive performance metrics:

- Accuracy Score: ~90.54%
- ROC AUC Score: ~90.54%
- Recall Score: ~88.60%
- Precision Score: ~92.17%
- F1 Score: ~90.35%

This model provides valuable insights for the bank to proactively address customer retention strategies and minimize churn.

### Conclusion

Predicting customer churn in a bank is crucial for improving customer retention, reducing revenue loss, and enhancing business strategies. This project demonstrates the power of machine learning in addressing real-world business challenges.

---
