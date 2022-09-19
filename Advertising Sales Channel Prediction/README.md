
# Advertising Sales Channel Prediction

The case study of Sales channel includes the detailed study of TV, radio and newspaper channel. The predict the total sales generated from all the sales channel.

First we have to do a detailed analysis of the data given in the dataset by loading , checking if there is any null value or not.

Then we will remove the unnecessary columns from the dataset which are not required.

There are many columns with string values. We will convert into readable numerical data.
dropped column named Unnamed: 0 

Then with heatmaps we will check the correlation values.

Then we will do visualization using different types of plot to compare and analyse the data and compare with dependent variable.
In the above plot,data is highly distributed in TV, then newspaper, then radio

Above boxplot shows that only newspaper has few outliers

Above distribution plots show that only newspaper has few skewness

there is a large difference between 75% and maximum for newspaper . So outliers are present in this dataset. Lets see it with visualization.
outliers are removed using Zscore.Skewness removed power_transform.

Using DecisionTreeClassifier,RandomForestClassifier,AdaBoostClassifier,LinearRegression model , we take out the accuracy score, 94% and Random State is 90

Scores for  LinearRegression() is 0.8958270968555071
Scores for  DecisionTreeRegressor() is 0.956716695914914
Scores for  RandomForestRegressor() is 0.9765219596006037
Scores for  AdaBoostRegressor() is 0.9517650311962944

After performing GridSearchCV method accuarcy is 96.62%

After hyperparamete tuning,our accuracy has been improve.we are getting 87.74% accuracy
