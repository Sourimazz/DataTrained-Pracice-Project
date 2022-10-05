
# HR Analytics Project- Understanding the Attrition in HR

Load the data sets
our data set has 1470 rows and 35 columns
here we can see that EmployeeCount, Over18 and StandardHours columns has only one unique value, hence we can drop this columns
we can see that out of 1469 No Attrition rate is higher than yes attrition

we can see that "non-travel" percentage is very lower than "travel-rarely"
above figure we can see that "lifescience" education field is very higher and "Human Resources" education fields is very lower.
above figure is showing "male" is higher than "female" .
here we can see that "sales executive" job role is very higher than rest of the job role.above figure see that very low percentage of emloyee is doing overtime

We can see positive relation between JobLevel and Age, for Gender Male its dropping after 55 age.
We can see negative relation between JobLevel and Attrition for both the genders male and female

After performing label encoder technique data is converted in numrical type
there is a large difference between 75% and maximum for some columns.so outliers are present in this dataset.lets see its with visualization.
Checking the columns which are positively and negative correlated with the target columns:

Above figure we can see that "Business Travel" is no correlation with each other, "performanceRating" & "HourlyRate" is very low correlation with each other . so we will drop this columns
We can see distribution is uneven in many columns

skewness are present in our datasets. need to remove it.
Above pairplot shows that relation between each and every column of our dataset.
we have 5.64 percentage data loss for removing outliers
Keeping +/-0.5 as the range for skewness.now skewness has been remove succesfully

Best accuracy is 0.8900862068965517 on Random State 34
Accuracy for DecisionTreeClassifier is 87.28%, for SVC its 92.24% and for AdaBoostClassifier its 88.57% and for Logisticregressionis 81.251
With SVC model there is very less difference in accuracy and cross validation score, Hence the best model is SVC.
After hyperparamete tuning,our accuracy has been improve.we are getting 96.33% accuracy

