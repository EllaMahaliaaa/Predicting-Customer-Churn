# Predicting-Customer-Churn
#The analysis began by importing the necessary dependencies and loading a dataset of 7,043 telecommunications customers into a pandas DataFrame. This dataset included a variety of features such as customer demographics, service usage details, billing information, and churn status, which are critical to understanding customer behavior. After conducting an initial data assessment, it was confirmed that the dataset had no missing values, ensuring a robust foundation for further analysis.

A correlation matrix was generated to examine relationships between numerical variables, followed by a series of visualizations to explore the distribution of key features. For example, a significant portion of customers were on month-to-month contracts, with fiber optic being the most widely used internet service, and electronic check payments being the most common payment method. Additionally, a churn rate of approximately 26% was identified, providing valuable context for understanding customer retention challenges.

To prepare the data for predictive modeling, categorical variables were encoded using one-hot encoding, transforming them into numerical features suitable for machine learning algorithms. Once the data was cleaned and preprocessed, a linear regression model was developed to predict whether a customer was a senior citizen, based on features such as contract type, payment method, and service preferences.

The dataset was split into training and testing sets, and the linear regression model was fitted to the training data. The model demonstrated exceptional performance, achieving an R² score of 1.0 on the test data, signifying a perfect fit. Evaluation metrics such as the mean squared error (MSE) and root mean squared error (RMSE) were minimal, further confirming the accuracy of the model's predictions.

In conclusion, this analysis not only provided valuable insights into customer behavior and churn, but also demonstrated proficiency in data preprocessing, feature engineering, and the application of machine learning techniques to real-world data. The model's accuracy highlights the effectiveness of using linear regression for this type of predictive analysis, making it a valuable tool for future business applications.







