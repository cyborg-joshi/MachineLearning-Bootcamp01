Aim – To predict the diabetes .

Dataset Description --
We have one csv files form kaggle related to diabetes.
sales -
	1-diabetes(1).csv
	
file.csv  file contain both input and output variable(s). We need to predict the sales for the predict.csv data set.

 
Libraries Used --

1. Numpy is used as np for linear algebra in our dataset.
2. Pandas is used as pd for data processing.
3. OrdinalEncoder from sklearn.preprocessing is used to interpret the ordinal datatypes.
4. train_test_split from sklearn.model is used for spliting the csv file into two different parts for training and testing and this traing and testing file is further divided into into two parts x and y value i.e. input and output values . 
5. LinearRegression from sklearn.linear_model is used as model for our data prediction.
6. mean_absolute_error, mean_squared_error from sklearn.metrics is used to find absolute and mean square error for our model to estimate the model accuracy.
7. sns is imported from seaborn to see the relationship between different column with outcome variable at a same time.
Footer
