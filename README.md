# Mexico_City_Realstate_Price_prediction

This project is tries to solve onne of the classical broblems in machinelearning which is Regression.
our dataset is Mexico_City_Realstate_Price collected for a long time.
even though we have a lot of features in our dataset i try to clean it so that only important feratures are used for model development.

        Cleaning Criteria

Subset the data in the CSV file and return only apartments in Mexico City ("Distrito Federal") that cost less than $100,000.
Remove outliers by trimming the bottom and top 10% of properties in terms of "surface_covered_in_m2".
Create separate "lat" and "lon" columns.
Mexico City is divided into 15 boroughs. Create a "borough" feature from the "place_with_parent_names" column.
Drop columns that are more than 50% null values.
Drop columns containing low- or high-cardinality categorical values.
Drop any columns that would constitute leakage for the target "price_aprox_usd".
Drop any columns that would create issues of multicollinearity.

 Algorithm Used

Ridge Linear Regression

FUTURE
we can imporove the accuracy if we can use 
Decision Tree regressor   or any other algorithm.
