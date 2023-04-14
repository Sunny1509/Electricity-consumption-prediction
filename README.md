# Electricity-consumption-prediction

**1. Setting the research goal**

The first step is to identify the research goal of the project. Our task is to predict the energy consumption across European Countries and hence our problem is regression. 

**2. Loading data and EDA**

First the data is loaded into the pandas dataframe and than the description of dataset is observed. The dataset contains 27 unique features. Analysis of each feature is carried out after identifying potential error in the data. **Outliers** are detected and removed from the data.

**3. Data Modeling**

For this problem two models have been selected
1. Elastic net Regression model
2. Random Forest Regressor

**4. Hyperparameter tuning**

For both the model the parameters are tuned via hyperparameter methods such as adding L1/L2 regression and cross validation.

**5. Scoring Metrics**

For this problem MSE and RSME have been used to evaluate the model.

**6. Ultimate judgement**

The Best performing model is selected to solve the given problem of predicting energy usage and feature importance has been carried to find the top features responsible for solving the problem.



