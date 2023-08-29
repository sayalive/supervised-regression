# supervised-regression
# Project Name - Retail Sales Prediction
# Project summary:
The Retail Sales prediction capstone project is provided with two CSV files that is Rossmann Stores Data and Store that consists of 19 variables which contains different kinds of information.

A) Initially, data cleaning and wrangling were conducted to combine two datasets. Then, the Exploratory Data Analysis (EDA) was performed by creating various visualization charts to analyze the data. During the EDA, some interesting findings were discovered such as the high correlation between sales and customers, more sales on Mondays due to store closures on Sundays, promotions leading to more sales, stores staying open more frequently during school holidays and generating more sales compared to state holidays, store type 'a' having the highest sales on average, Assortment level-b (i.e., 'extra') resulting in the highest average sales, school holidays affecting only 17.9% of sales, and so on.

B) In the second step I did hypothesis testing:

Hypothesis: Stores located closer to competition have significantly lower sales than stores located further away

Null hypothesis: There is no significant difference in sales between stores closer to the competition and farther away.

Alternative hypothesis: Stores closer to competition have significantly lower sales than stores farther away.

To test this hypothesis, I performed a two-sample t-test between the sales of stores located within 10 km of competition and stores located further away. We can set a significance level of 0.05

C) In the third step I performed feature engineering like filling missing values, handling null values, handling columns, deleting unnecessary columns, feature processing, feature extracting, outliers handling and feature selection.

D) The last but not the least step, of my project is "model deployment". I have deployed two models, first one is the "linear regression model" and the second one is the "lasso regression model".The Retail Sales prediction data is provided with two csv files that is Rossman and Stores which contains different variables of information.It consists combinly about 19 variables which contain different kind of information

As the first step of the project we have performed data cleaning as well as data wrangling by merging both of tables in the next step we have performed Exploratory Data Analysis(EDA) in which we created different visualization charts to analyze the data we found that some interesting facts like sales are highly correlated with customers,there were more sales on Monday,probably because shops are closed on Sundays,it could be seen that the promo leads to more sales,more stores open on school holidays than on state holiday and hence had more sales than state holidays,on an average store type B had the highest sales,Highest average sales were seen with Assortment levels-b which is ‘extra’,82.1% sales are not affected and only 17.9% sales is affected because of school holiday etc.

In the next step I have done hypothetical testing Hypothesis: Stores located closer to competition have significantly lower sales than stores located further away.Null hypothesis: There is no significant difference in sales between stores located closer to competition and stores located further away. Alternative hypothesis: Stores located closer to competition have significantly lower sales than stores located further away.To test this hypothesis, we can perform a two-sample t-test between the sales of stores located within 10 km of competition and stores located further away. We can set a significance level of 0.05

After that I have performed feature engineering like filling missing values,handling of null values,handling columns,deleting unnecessary columns,feature processing,feature extracting,Outliers handling,feature selection.

In the last step most important step of my project that is model deployment. I have deployed two models first one is the linear regression and second one is the lasso regression final conclusion of both of the models -The MSE and R2 score are commonly used evaluation metrics for regression models. In this case, the Linear Regression and Lasso Regression models have very similar performance, with the Lasso Regression model having a slightly lower MSE and a slightly higher R2 score.The mean squared error (MSE) measures the average squared difference between the predicted and actual values, where a lower MSE indicates better performance.The Rsquared (R2) score measures the proportion of the variance in the dependent variable that is predictable from the independent variables, where a higher R2 score indicates better performance.

# Objective:
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.
