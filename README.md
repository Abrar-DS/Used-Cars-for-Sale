This project aim to perform data preprocess,analysis functions and predict accurate machine learning models.
In this project we use a large dataset. It consists of 16 columns and 3.5 million rows that contains data of cars for sale.
The data set contains 13811308 missing values, unexpected data in 4 columns and outliers in 140181 rows. 
These problems have been solved by replacing missing values with mean and mode, dropping unexpected data, and using z-score to find and delete outliers. 
For the EDA, we deducted some statistical results and correlation coefficients among all the variables in the dataset. 
Moreover, we applied a normality and transformed the data when needed. 
In building models part, we applied two regression models (Random Forest Regressor and Gradient Boosting Regressor) then performed hyper-parameter tuning. 
We found that the result of the mean squared error is significant improvement compared to the previous models.
