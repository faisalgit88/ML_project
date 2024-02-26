## End to End Machine learning project
## This Project to demostrate end to end project in structured programming.
this project using Visual Studio Code and following standard machine learning project flow.

Objective of this project is to create a prediction model using the best machine learning model.

Student Performance Indicator
Life cycle of Machine learning Project
Understanding the Problem Statement
Data Collection
Data Checks to perform
Exploratory data analysis
Data Pre-Processing
Model Training
Choose best model

1) Problem statement
This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.

2) Data Collection
Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
The data consists of 8 column and 1000 rows.

2.1 Import Data and Required Packages
Importing Pandas, Numpy, Matplotlib, Seaborn and Warings Library.

2.2 Dataset information
gender : sex of students -> (Male/female)
race/ethnicity : ethnicity of students -> (Group A, B,C, D,E)
parental level of education : parents' final education ->(bachelor's degree,some college,master's degree,associate's degree,high school)
lunch : having lunch before test (standard or free/reduced)
test preparation course : complete or not complete before test
math score
reading score
writing score

3. Data Checks to perform
Check Missing values
Check Duplicates
Check data type
Check the number of unique values in each column
Check the statistics of the data set
Check various categories present in the different categorical column
Feature Engineering

4. Exploring Data ( Visualization )
4.1 Visualize average score distribution to make some conclusions.
Histogram
Kernel Distribution Function (KDE)
and a lot more methods are used to visualize the data and understand the relationship.

________________________________________________________________________________________

5. Model Training
   # Modelling

KNeighborsRegressor: Regression model
DecisionTreeRegressor: Regression model
RandomForestRegressor: Regression ensemble model
AdaBoostRegressor: Regression ensemble model
SVR: Regression model
LinearRegression: Regression model
Ridge: Regression model
Lasso: Regression model
CatBoostRegressor: Regression model
XGBRegressor: Regression model

RandomizedSearchCV: Model selection/parameter tuning technique


Set Our Target variable : Math score
- Use Column Transformer:
    Standard scaler for Numerical feature 
    One hot encoding for Categorical feature
- Split train test set
- learn
- evaluate
- here is summary of the R2 score
- 	Model Name	R2_Score
2	Ridge	0.880593
0	Linear Regression	0.879046
7	CatBoosting Regressor	0.851632
5	Random Forest Regressor	0.851423
8	AdaBoost Regressor	0.845744
6	XGBRegressor	0.827797
1	Lasso	0.825320
3	K-Neighbors Regressor	0.782192
4	Decision Tree	0.747430





