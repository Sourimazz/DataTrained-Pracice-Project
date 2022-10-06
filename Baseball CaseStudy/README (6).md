
# Baseball Case Study 

our datasets has 30 rows and 17 columns
Datasets does not contain any missing values.Lets see it with visualization
We can see positive relationship between Saves and Wins
With Walks also we can see some positive linear relationship.

Hits column has neither positive nor negative relation with our target columns(Wins)
We can see positive linear relationship between Runs Allowed and Earned Run Average (ERA) column.
We can see when Wins are getting increase, Earned run Average(ERA) is getting decreased.

Frequency of error is as low as 1 and as high as 9 where in the range starts from around 75 and ends around 125

We can see negative relationship between Wins and Runs Allowed column.
We can see negative relationship between Wins and Earned Runs column.

We can see negative relationship between Wins and Earned Run Average column.

Maximum value in complete Game columns are 0 and 1, also we it does not contain value value 8 and 9
 
We can see there are some outliers in some columns
We can see distribution is uneven in some columns

All the values of skewness are in range of -0.5 to +0.5 except Runs,Hits,Complete Game,Saves and Errors column.

there is a large difference between 75% and maximum for some columns.so outliers are present in this dataset.lets see its with visualization.
 
Checking the columns which are positively and negative correlated with the target columns:

Our target column 'wins' has high positive correlation with Runs, Doubles, homeruns, walks, shutouts and saves columns, whereas it has high negavtive correlation with Runs Allowed, Earned Runs and Earned Run Average(ERA)
percentage of data loss is 3.33
now skewness has been remove using power transform

Best accuracy is  0.9508451216581015  at Random State  104

With ElasticNet model there is very less difference in accuracy and cross validation score, Hence the best model is ElasticNet.
After performing GridSearchCV method accuarcy is 81.77%

load the model from the disk



