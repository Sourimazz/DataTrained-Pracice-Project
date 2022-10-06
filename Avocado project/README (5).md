
# Avocado Project

load top 10 data sets
we have 18249 rows and 14 columns
Datasets does not contain any missing values.Lets see it with visualization
Better better visuliazation lets change the format of date column.

outliers are present in our data sets
skewness has present in our datasets

here we can see that all dataset are lies in your nature
there is a large difference between 75% and maximum for maximum columns.so outliers are present in this dataset.lets see its with visualization.

above figure is the correlation with each other .
 Lets see its with visualizationabove figure is the correlation with each other . Lets see its with visualization

Checking the columns which are positively and negative correlated with the target columns:
maximum columns are negative correlation with the target columns
now remove all outliers

All the values of skewness are in range of -0.5 to +0.5.so finally skewness has been remove successfully
Best accuracy is 0.5001331209179911 at Random State 188

With LinearRegression model there is very less difference in accuracy and cross validation score, Hence the best model is LinearRegression.

After performing GridSearchCV method accuarcy is 43.93%

we will do Classification Problem
 
 we will follow the same process data does not contain any missing values. lets see its with visualization.
 After hyperparamete tuning,our accuracy has been improve.we are getting 85.24% accuracy
 load the model from the disk
