# California Housing Dataset

## Introduction

<p> The problem addressed in this project is use characteristics such as the number of rooms, population, and location in California for predicting the median value. This is a relevant problem for the real estate industry and can aid in making informed decisions. The motivation for the use of AI is to accurately predict the house values and provide insights to the real estate industry. The originality of the project lies in the use of multiple regression algorithms to predict the house values accurately.</p>

## Importing Packages and Loading the Data Set
<p>This code imports the Pandas package for data analysis. It then loads the "housing.csv" dataset into a Pandas DataFrame called "df". The "housing.csv" file, which offers details about California's housing costs, was used in this project. The dataset has 20640 records with 10 features. The data extraction effort for this project is low, as the dataset is readily available and requires minimal preprocessing. </p>

## Conclusion

<p> In this project, we used machine learning techniques to predict the median house value in various districts in California using a dataset with several features such as housing median age, total rooms,
total bedrooms, population, households, median income, and ocean proximity. First, we performed exploratory data analysis to gain insights into the data and identify any patterns or trends. We
visualized the data using various plots and graphs such as a histogram, count plots, and correlation matrix. We also pre-processed the data by dropping null values and converting the categorical
feature 'ocean proximity' into numerical values.
Next, we defined several regression models such as Linear Regression, Ridge, etc., and evaluated their performance using mean squared error (MSE). We also used GridSearchCV to optimize the
hyperparameters of the Random Forest model. Finally, we used the best performing model to predict the median house values and evaluated the model's performance using a scatter plot of actual
versus predicted values. Overall, our best performing model was the Random Forest Regression with an MSE of 0.17 and an R2 score of 0.81, indicating that it is a good fit for the data. The scatter
plot showed a good fit between the actual and predicted values, with most points clustering around the diagonal line.
In conclusion, this project demonstrates how machine learning techniques can be used to predict real estate prices, and highlights the importance of exploratory data analysis and model selection in
achieving accurate predictions.</p>
