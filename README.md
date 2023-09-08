# Prediction_using_ML

Project Title: Predicting Student Scores Based on Study Hours

Author: Shruthi H

Introduction:

The goal of this project is to create a predictive model that estimates a student's percentage score based on the number of hours they spend studying. This project has various steps, including data collection, preprocessing, exploratory data analysis (EDA), model training, and evaluation.

Step 1: Importing Python Libraries:

This step involves importing essential Python libraries, such as pandas, numpy, matplotlib, seaborn, and scikit-learn, which will be used for data manipulation, visualization, and machine learning.

Step 2: Importing the Dataset:

The dataset containing student data is imported using pandas. The dataset is presumably stored as a CSV file.

Step 3: Checking Data:

The code checks the imported data for basic information, such as the shape of the dataset and data type information.
It also checks for missing values and duplicated records. In this case, there are no missing or duplicated records, indicating a clean dataset.

Step 4: Data Visualization:

This step involves visualizing the data to gain insights. The code creates various plots, including a scatter plot, a bar chart, and a line graph, to explore the relationship between study hours and percentage scores.
The visualizations suggest that there is a positive correlation between study hours and percentage scores.

Step 5: Preparing the Data:

Data is prepared for model training by separating it into feature variables (study hours, x) and target variables (percentage scores, y).

Step 6: Splitting the Data for Training and Testing:

The dataset is divided into a training set and a testing set using scikit-learn's train_test_split function. This is essential to evaluate the model's performance.

Step 7: Model Training:

A linear regression model is chosen for this project, and it is trained using the training data. Linear regression is a suitable choice for predicting continuous numerical values like percentage scores based on study hours.

Step 8: Model Evaluation:

The trained model is evaluated using Mean Absolute Error (MAE), which measures the average absolute difference between the actual and predicted scores. A lower MAE indicates a better-performing model.

Predicting Scores for a New Data Point:

The model is used to predict the percentage score for a hypothetical scenario where a student studies for 9.25 hours per day.


