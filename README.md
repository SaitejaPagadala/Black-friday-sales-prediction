# Black-friday-sales-prediction

Black Friday Sales Prediction Using Regression Algorithms

1. Introduction
The goal of this project is to predict Black Friday sales using regression algorithms. Accurately predicting sales can help retailers optimize their inventory management and marketing decisions. In this project, we'll use a dataset of historical Black Friday sales to train and evaluate several regression algorithms.

2. Dataset
The dataset we used was obtained from Kaggle, and contains information about Black Friday sales at a large retail store. The dataset includes features such as age, gender, occupation, and marital status of customers, as well as product category and purchase amounts. Before training our model, we preprocessed the data by filling missing values, encoding categorical features, and scaling numerical features.

3. Exploratory Data Analysis (EDA)
We started by exploring the distribution of the target variable, total purchase amount, and other features to gain insights into the data. We plotted histograms and barplots of different features to visualize their distributions and relationships. We also calculated correlations between features to identify any multicollinearity or relationships between features.

4. Feature Engineering
After EDA, we created new features such as "total number of items purchased by a customer", and "number of times a customer has made a purchase in the past" to improve the predictive power of our model. We also one-hot encoded categorical variables to allow the model to learn from the categorical data.

5. Model Selection
We tested several regression algorithms including linear regression, decision tree regression, and random forest regression. We compared the performance of each model using metrics such as mean absolute error, mean squared error, and R-squared, and selected the best model for our problem.

6. Model Evaluation
After selecting the best model, we evaluated its performance on a holdout set of data that the model had not seen before. We plotted the predicted sales vs. actual sales to visualize the performance of the model. The model achieved an R-squared score of 0.7, which indicates a reasonable fit to the data.

7. Conclusion
Our model could be used to help retailers optimize their inventory management and marketing strategies by predicting Black Friday sales accurately. However, there are several limitations to the model, such as the fact that it only uses historical sales data and does not take into account external factors such as economic conditions or weather. To improve the model, we could incorporate additional data sources and experiment with more advanced regression algorithms.

8. Code
The code for this project is available in the code directory. The data directory contains the cleaned and preprocessed dataset we used for the project.

9. Requirements
The code was developed using Python 3.8 and requires the following packages: pandas, numpy, sklearn, matplotlib, seaborn. The packages can be installed using pip.
