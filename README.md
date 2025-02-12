# Medical-Insurance-Prediction
This project predicts medical insurance charges based on patient details using Multiple Linear Regression. The dataset includes factors such as age, sex, BMI, number of children, smoking status, and region.

This project focuses on predicting medical insurance costs using Multiple Linear Regression. It utilizes a dataset containing various patient attributes that influence insurance charges, such as age, gender, BMI, number of children, smoking status, and region. The goal is to develop a predictive model that estimates insurance costs based on these factors.

Project Workflow:
Data Loading and Preprocessing:
The dataset is read using Pandas.
Categorical variables (sex, smoker, and region) are converted into numerical values to make them suitable for machine learning algorithms.
Feature Selection and Target Variable:

The independent variables (features) include age, sex, BMI, number of children, smoker status, and region.
The dependent variable (target) is the insurance charges.
Data Splitting:

The dataset is split into training (80%) and testing (20%) sets using train_test_split to evaluate model performance.
Model Training:

A Multiple Linear Regression model is trained using the training dataset.
The model learns the relationship between input features and insurance charges.
User Interaction (Menu-Driven System):

The system provides three options:
Predict Insurance Charges:
Users input patient details (age, sex, BMI, children, smoker, and region).
The trained model predicts insurance charges based on the provided data.
View Model Accuracy:
The model's performance is evaluated using the R² score, which indicates how well the model explains the variance in insurance charges.
Exit:
The program terminates when the user chooses to exit.
This project helps in understanding the application of regression models in real-world scenarios, particularly in insurance cost estimation. It demonstrates how machine learning can be used to analyze historical data and make predictions based on new inputs.
