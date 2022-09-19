
# Big Data Mart Sales Problem

The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store.

Load the dataset,we have 8523 rows and 12 columns in our dataset,item weight, outlet size has null values.

We have missing values in two columns: Item_Weight, Outlet_size.
Item_MRP is positively correlated with Item_Outlet_Sales. All other columns has negative correlation with Item_Outlet_Sales. Also Item_Weight has very low correlation with Item_Outlet_Sales.

Item_Visibility, Item_MRP and Item_Outlet_Sales are numerical type hence number of unique values are high in these columns, all other columns are object type or categorical

we have replaced null values of Item_Weight column with mean

Let's see Visualization using different plots

We can see outliers in Item_visibility column.some skewness has preset here.We are checking correlation of columns after encoding.
Then perform standardization.

Using LinearRegression,DecisionTreeRegressor,RandomForestRegressor,AdaBoostRegressor model, Best accuracy is  0.55 and Random State is 82

Score for LinearRegression() is:  0.5149819063278622
Score for DecisionTreeRegressor() is:  0.15816828039376615
Score for RandomForestRegressor() is:  0.5389835484202757
Score for AdaBoostRegressor() is:  0.5454703814438581
With LinearRegression model there is very less difference in accuracy and cross validation score, Hence the best model is AdaBoostRegressor.

After performing GridSearchCV method accuarcy is 54.20%

Using Test DataSet, all the process is same.

Then load the model.