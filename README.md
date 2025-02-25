# Titanic Survival Prediction Using Machine Learning
## Importing Libraries
In this project, I import essential libraries that play pivotal roles in enhancing data manipulation and visualization capabilities:

pandas: A versatile library for data manipulation and analysis, enabling me to handle tabular data structures effectively.

numpy: A fundamental library for numerical operations and computations, empowering me with efficient mathematical operations on arrays.

seaborn: A powerful data visualization library based on matplotlib, simplifying the creation of informative statistical graphics.

matplotlib.pyplot: A widely used library for creating plots and charts, crucial for visualizing my data and analysis results effectively.

## Loading Data
My project's analysis relies on Titanic passenger data, which was loaded from CSV files using pandas and separated into training and testing sets, 
providing the essential information for prediction.

## Exploratory Data Analysis
To gain a thorough understanding of the data, I conducted Exploratory Data Analysis (EDA). This involved visualizing the distribution of numerical features 
like age, SibSp, Parch, and fare to identify patterns and outliers, as well as exploring relationships between variables to uncover potential correlations
influencing survival.

## Data Cleaning
Data cleaning proved essential for the success of my analysis. During this phase, I addressed missing values, removed uninformative columns, and created new 
features to improve model performance

## Model Testing
My project involves rigorous model testing to determine the best approach for predicting passenger survival on the Titanic. I evaluate multiple machine learning models,
including Decision Tree, RandomForest, KNeighbor Classifier, and Logistic Regression. The culmination of my efforts is a model with an impressive 76.6% accuracy, 
showcasing its ability to make accurate predictions.

## Test Submission
With my chosen model in place, I apply it to predict survival on the test dataset. I then create a submission file, a critical step for evaluation purposes, allowing me to 
see how well my model generalizes to new and unseen data.

## Conclusuion
At a predictive accuracy of 76.6%, my model demonstrates its potential to forecast Titanic passenger survival effectively. This project not only illustrates the practical
application of machine learning techniques on historical data but also provides insights into the influential factors behind survival rates during the Titanic disaster.
