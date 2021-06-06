# Item-Outlet-Sales-Prediction
## Using KNN-Regressor Algorithm
### Problem Statement
Make a machine learning model that predicts the Sales of particular item of a Big Mart.</br>
It would be nice for the big mart to have a model which can predict the sales. This can help them to plan accordingly for a better service and profit.
Some marts are also using this kind of model to estimete the sales
### About the Dataset
The Dataset contains the information of Outlets and items in the outlet such as:
* Item Identifier
* Item Fat Content
* Item Visibility
* Item Type
* Item MRP
* Item weight
* Outlet Identifier
* Outlet Type
* Outlet Location type
* Outlet Size
* Outlet Establishment Year
* Item Outlet Sales
### Attributes Information
* Item_Identifier: It is a unique identity for all items in superstore.
* Item_Weight: It is the weight of each item.
* Item_Fat_Content: It is the categorical column which tells whether the fat content in item is Low Fat, Regular, High Fat
* Item_Visibility: It tells about the visibility of the item.
* Item_Type: It is the Categorical column which describe the category of the item(Fruits and Vegetables, Snack Foods, Household, Frozen
Foods, Dairy, Canned, Baking Goods, Health and Hygiene, Soft Drinks, Meat, Breads, Hard Drinks, Others, Starchy Foods, Breakfast, Seafood.
* Item_MRP: As the name tells, it is the MRP of each Item.
* Outlet_Identifier: It is the categorical column that has the unique identity of the each outlet.(OUT027, OUT013, OUT035, OUT049, OUT046,
OUT045, OUT018, OUT017, OUT010, OUT019)
* Outlet_Establishment_Year: It is the Establishment year of the Outlet(1985, 1987, 2004, 1997, 1999, 2002, 2009, 2007, 1998)
* Outlet_Size: It is the categorical column which tells whether the size of Outlet is Small, Medium, Large.
* Outlet_Location_Type: Loacation is Tier1, Tier2, Tier3.
* Outlet_Type: It is the Type of the Outlet.(Supermarket Type1, Supermarket Type2, Supermarket Type3, Grocery Store)
* Item_Outlet_Sales: It is the Target column which describes the sale of the particular item in the Particualar Outlet.
### Libraries Used
* Numpy
* pandas
* Matplotlib
* Seaborn
* Sklearn
### Steps Performed
* Import the Essential Libraries
* Load the Dataset
* Analyse the Data
* Detect & Treat the Missing Values
* Detect & Remove the Outliers
* Check the Datatypes of each column and change them as per needs
* Correct the speeling Errors if present in the Data set
* Deleting Unnecessary Data
* Perform Visual Analysis for  better understanding
* Perform Univariate Analysis
* Perform Bivariate Analysis
* preprocess the Data by Normalizing it
* Split the Data into Train & Test sets
* Making the Elbow curve to decide the right value of n-neighbours to make the KNN-Regressor
* Fitting the Mode
## Model Successfully Created

[Big_Mart_Sales_Predction.pdf](https://github.com/devgarg9966/Item-Outlet-Sales-Prediction/files/6604369/Big_Mart_Sales_Predction.pdf)
