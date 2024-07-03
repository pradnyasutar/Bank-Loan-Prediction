# Bank Loan Prediction for Customer Retention
# Objective:
The primary goal of this project is to predict loan statuses of customers to develop focused customer retention programs. By analyzing customer data, the project aims to identify key factors that influence loan defaults, enabling the bank to take proactive measures to retain customers and mitigate financial risk.

# Overview:
With a dataset containing various attributes of loan applicants, including demographic information, financial details, and loan history, the project employs advanced data processing and machine learning techniques to build a predictive model. This model will help in identifying potential defaulters, thereby allowing the bank to implement strategic retention programs.

# Data Pre-Processing:
The dataset undergoes thorough preprocessing to ensure accuracy and reliability. 
# This involves:
Removing Irrelevant Variables: The 'Loan_ID' column is dropped as it does not contribute to the prediction.
Univariate Analysis: Data types and missing values are checked and handled appropriately.
Outlier Detection: Box plots are used to identify and address outliers in the dataset.
Categorical Variable Encoding: Categorical variables are converted into numerical format using Label Encoding to make them suitable for machine learning algorithms.
# Exploratory Data Analysis (EDA):
EDA is conducted to understand the distribution and relationships within the data. Key insights include:

# Churn Rate Analysis:
The distribution of the target variable 'Loan_Status' is visualized to understand the proportion of approved and rejected loans.
# Subsetting Data: 
Numerical and categorical variables are separated and analyzed individually.
# Data Partitioning:
The dataset is split into training and testing sets to evaluate the model's performance. This ensures that the model is tested on unseen data, providing an unbiased evaluation of its predictive power.

# Model Building:
A Decision Tree Classifier is chosen for its interpretability and effectiveness. The initial model is built and trained on the training set, providing a clear visual representation of the decision-making process through a plotted tree.

# Model Improvement:
To enhance the model's accuracy and prevent overfitting, pruning techniques are applied. This involves setting parameters such as minimum samples for splitting nodes and maximum tree depth, resulting in a more generalized and robust model.

# Performance Evaluation:
The model's performance is evaluated using various metrics such as precision, recall, and F1-score. These metrics provide a comprehensive understanding of the model's accuracy in predicting loan statuses on both the training and testing datasets.

# Final Model:
The improved model demonstrates high accuracy and is capable of effectively predicting loan statuses. This model is then exported for future use, ensuring its application in real-world scenarios.

# Strategic Insights:
The project provides actionable insights into customer retention strategies. By identifying high-risk customers, the bank can implement targeted programs to improve customer satisfaction and reduce the likelihood of loan defaults. For instance, customers with higher monthly charges and shorter tenure periods may require personalized support and retention initiatives.

# Conclusion:
This project successfully builds a predictive model for bank loan statuses, offering valuable insights into customer behavior. By leveraging this model, the bank can enhance its customer retention efforts, minimize financial risks, and foster long-term customer relationships.
