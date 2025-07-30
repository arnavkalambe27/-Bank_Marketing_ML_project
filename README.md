# Bank  Marketing ML project
## Project Overview
This project involves building a classification model to predict a target variable based on the provided bank-full.csv dataset. The key steps undertaken are:
Data Loading and Preprocessing: The bank-full.csv dataset is loaded. The target variable 'y' is separated from the features. Categorical features are identified and then transformed using One-Hot Encoding. Numerical features are identified.

Data Splitting: The combined features are split into training and testing sets to prepare for model training and evaluation.

Feature Scaling: Numerical features are scaled using two different methods:

StandardScaler: This method scales features to have a mean of 0 and a standard deviation of 1.

MinMaxScaler: This method scales features to a fixed range, typically between 0 and 1.

Model Training and Evaluation: A Logistic Regression model is trained on the data scaled using StandardScaler. The model's performance is then evaluated using metrics such as accuracy, precision, recall, F1-score, and a confusion matrix. The next planned step is to evaluate the model using MinMax scaled data.
