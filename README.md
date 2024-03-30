# CUSTOMER CHURN PREDICTION

![image](https://github.com/ifeyinwaibekwe/Customer-Churn-Prediction/assets/149434454/707ca8a3-11aa-48ba-8c4e-92f59339cd45)


## Table of Contents
- [Project Overview].(#project-overview).
- [Project Objective].(#project-objective).
- [Data Source].(#data-source).
- [Data Preprocessing].(#data-preprocessing).
- [Machine Learning Model].(#machine-learning-model).
- [Evaluation Metrics].(#evaluation-metrics).
- [Key Insights].(#key-insights).
- [Conclusion].(#conclusion).
- [Recommendations].(#recommendations).

## Project Overview
This project focuses on developing a robust customer churn prediction system for ConnectTel Telecom Company to address the challenge of customer attrition. Leveraging advanced analytics and machine learning techniques, the system aims to accurately forecast customer churn, implement targeted retention initiatives, reduce customer attrition, enhance customer loyalty, and gain a competitive edge in the telecommunications industry.

## Project Objective
The objective of this project is to build and train a robust machine learning model that can accurately predict customer attrition for ConnectTel Telecom Company. By leveraging advanced analytics and machine learning techniques on available customer data, the model aims to forecast customer churn, implement targeted retention initiatives, reduce customer attrition, enhance customer loyalty, and gain a competitive edge in the telecommunications industry.

## Data Source
The dataset utilized in this project was supplied by ConnectTel and comprises various features derived from online transactions. These features encompass information such as gender, senior citizen status, tenure, presence of dependents, partnership status, phone service subscription, availability of online security and tech support, contract details, and other pertinent data points.

## Data Preprocessing
In this project, thorough data preprocessing was conducted to ensure the quality and integrity of the dataset. The preprocessing steps included:I Checked for missing data and handled missing values appropriately.
Checked for and removed duplicates in the dataset. Examined both categorical and numerical features to identify redundant features and gain insights into the distribution of variables.Extracted date information into year, month, and quarter to facilitate temporal analysis. Scaled the dataset to ensure uniformity and prevent features with large magnitudes from dominating the model.Engaged in feature engineering to extract relevant information from the raw data, enhancing the predictive power of the model.

## Machine Learning Model
In this project, I developed a customer churn predictive model using a supervised machine learning approach. I split the dataset into training and testing sets with an 80:20 ratio to facilitate model training and evaluation.
I experimented with seven classification algorithms, including but not limited to: 

-**Logistic Regression**
-**Random Forest**
-**Support Vector Machine**
-**Decision Tree Classifier**
-**SGD Classifier**
and others
 After extensive experimentation and hyperparameter tuning, I assessed each algorithm's performance using metrics such as accuracy, precision, recall, and ROC AUC score. This evaluation led to the identification of the most suitable algorithm for predicting customer churn.

## Evaluation Metrics
Machine learning model performance was accessed using the following Evaluation metrics:

-**Acurracy** : Indicates the overall correctness of the model's predictions.
-**precision**: Represents the accuracy of the model in identifying customers who are predicted to churn, among all customers predicted to churn
-**Recall** : Indicates the ability of the model to correctly identify all customers who actually churned, among all customers who churned.
-**ROC AUC** : Assesses the model's ability to distinguish between churn and non-churn instances.

# Key Insights
Model Performance Analysis: The evaluation of various machine learning algorithms revealed differing performances in predicting customer churn, with each model exhibiting distinct strengths and weaknesses.

SVC Classifier Precision: The Support Vector Classifier (SVC) model demonstrated a higher precision rate compared to other algorithms, indicating its effectiveness in accurately identifying customers at risk of churning. This suggests that SVC may be particularly suitable for minimizing false positive predictions and optimizing customer retention efforts.

Gradient Boosting Regressor Performance: Despite hyperparameter optimization, the Gradient Boosting Regressor model exhibited lesser performance compared to the SVC model, particularly in predicting positive customer attrition. This implies that while gradient boosting techniques may enhance overall predictive accuracy, they may still struggle with certain aspects of customer churn prediction.

Confusion Matrix Analysis: The analysis of confusion matrices for both models provided insights into their respective strengths and weaknesses in predicting customer churn. Specifically, the true positive rate (TPR) and false positive rate (FPR) were examined to assess each model's ability to correctly identify churners while minimizing misclassifications.

Optimal Model Selection: Based on the evaluation metrics and performance analysis, the SVC Classifier emerged as the most suitable model for predicting customer churn in this context. Its higher precision and comparable accuracy make it well-suited for identifying customers at risk of churning while minimizing false positives, thereby enabling more effective retention strategies.

Recommendation for Future Work: While the SVC Classifier demonstrated promising results, further exploration and refinement of predictive models, such as ensemble methods or neural networks, may offer additional improvements in predictive accuracy and robustness. Additionally, ongoing monitoring and evaluation of model performance are essential for adapting to evolving customer behavior and market dynamics.



## Conclusion 
In conclusion, the development of a robust customer churn prediction system is essential for ConnectTel Telecom Company to address the critical challenge of customer attrition. Through the evaluation of various machine learning algorithms, including Support Vector Classifier (SVC) and Gradient Boosting Regressor, we identified SVC as the most suitable model for predicting customer churn due to its higher precision and comparable accuracy. This indicates its effectiveness in accurately identifying customers at risk of churning while minimizing false positive predictions.

## Recommendations

Implementation of SVC Model: ConnectTel should prioritize the implementation of the SVC model for predicting customer churn in real-world scenarios. By leveraging its higher precision and accuracy, the company can proactively identify and target customers at risk of churning, thereby optimizing retention efforts and reducing overall customer attrition rates.

Continuous Model Monitoring and Evaluation: It is imperative for ConnectTel to establish a system for continuous monitoring and evaluation of the SVC model's performance. Regular assessments will enable the company to identify any deviations or fluctuations in predictive accuracy, allowing for timely adjustments and refinements to the model as needed.

Integration of Predictive Insights into Business Strategies: ConnectTel should integrate predictive insights from the churn prediction model into its business strategies and decision-making processes. By aligning retention initiatives with identified churn risk factors, the company can tailor its efforts to address specific customer needs and preferences, thereby enhancing customer satisfaction and loyalty.

Customer Feedback and Engagement: ConnectTel should actively seek feedback from customers and engage with them to understand their evolving needs and preferences. By fostering open communication channels and soliciting customer input, the company can gain valuable insights into factors influencing churn behavior and proactively address issues to improve overall customer experience.

Investment in Data Infrastructure and Analytics Capabilities: To support ongoing predictive modeling efforts, ConnectTel should invest in robust data infrastructure and analytics capabilities. This includes data collection, storage, and processing systems, as well as skilled data science talent to drive insights and innovation in customer churn prediction.

By implementing these recommendations, ConnectTel can effectively leverage predictive analytics to mitigate customer churn, foster stronger customer relationships, and ultimately drive business growth and sustainability in the telecommunications industry.








































