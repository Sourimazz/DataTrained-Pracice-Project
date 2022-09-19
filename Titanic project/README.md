
# Titanic Project

We have to predict if an arbitrary passenger on Titanic would survive the sinking or not.

First we have to do a detailed analysis of the data given in the dataset by loading , checking if there is any null value or not.

Then we will remove the unnecessary columns from the dataset which are not required.

There are many columns with string values. We will convert into readable numerical data.

Then with heatmaps we will check the correlation values.

Then we will do visualization using different types of plot to compare and analyse the data and compare with dependent variable.

Then we will check that there are outliers. Age,SibSp,Fare have outliers.

Also we will check the skewness or not.Those columns are skewness presesnt here

outliers are removed using Zscore.Skewness removed power_transform.

Using DecisionTreeClassifier,RandomForestClassifier,AdaBoostClassifier,SVC,LogisticRegression model , we take out the accuracy score, 85% and Random State is 93

Accuracy for DecisionTreeClassifier is 84.80%, for SVC its 79.41% and for AdaBoostClassifier its 77.94% and for RandomForestClassifier its 84.31%

Best model is RandomForestClassifier as there is very less differece model and cross validation compare to other models.
After hyperparamete tuning,our accuracy has been improve.we are getting 87.74% accuracy
