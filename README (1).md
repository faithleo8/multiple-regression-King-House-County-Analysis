
KING COUNTY HOUSING ANALYSIS 


Stakeholder:
Real Estate companies in King County.

Business Problem:
Real estate companies need information that would enable them offer home owners with advise on features to improve in their homes and the expected value increase that comes wit these improvements before they list their homes for sale.

Business Question:
What are some of the features that a home seller need to improve in order to sell their homes at a higher value?

Data Understanding
This project uses the King County House Sales dataset, which can be found in kc_house_data.csv in the data folder in this repo. The description of the column names can be found in column_names.md in the same folder.The original dataset includes sales data for 21,597 homes with 20 different features, which include:

~date - Date house was sold

~price - Sale price (prediction target)

~bedrooms - Number of bedrooms

~bathrooms - Number of bathrooms

~sqft_living - Square footage of living space in the home

~sqft_lot - Square footage of the lot

~floors - Number of floors (levels) in house

~waterfront - Whether the house is on a waterfront

~view - Quality of view from house

~condition - How good the overall condition of the house is. Related to maintenance of house

~grade - Overall grade of the house. Related to the construction and design of the house

~sqft_above - Square footage of house apart from basement

~sqft_basement - Square footage of the basement

~yr_built - Year when house was built

~yr_renovated - Year when house was renovated

~zipcode - ZIP Code used by the United States Postal Service

DATA CLEANING AND PROCESSING

1.Handling missing values.

2.Visualization and outliers

3.Exploring correlations

4.creating dummy variables

MODELLING THE DATA

1.Model creation

2.calculating the RMSE and Accuracy

3.Adjusted R-squared and mean Absolute Error Values

4.conclusion

5.Recommendations

REGRESSION OUTCOME

The model that does the best at predicting house sale prices for first time home buyers was the model comprising of all home features. Though the model did not have any statistical relationship with cond_Poor, grade_12 Luxury, and reno_status the R-squared value improved from the baselines Rsquared value(38.6% to 57.7%) The model can explain approximately 58% of variations in price.

Further, the Mean Absolute Error improved from our baseline score of 131366 to 105602, which is good enough.

In our final model, all features have a statistically significant linear relationship with sale price.

While holding all other variables constant, the addition of a bathroom increases sale price by 24,020 dollars

While holding all other variables constant, the addition of one floor level increases sale price by 41,050 dollars

While holding all other variables constant, improving a home's condition from Average to Very Good increases sale price by 42,180 dollars

While holding all other variables constant, improving a home's grade from Better to High Quality increases sale price by 72,690 dollars

While holding all other variables constant, addition of a basement to a home increases sale price by 40,450 dollars

While holding all other variables constant, increasing the sqft_living of a home increases sale price by 63.75 dollars

While holding all other variables constant, having a waterfront in a home increases sale price by 10,740 dollars

ADVICE TO HOME OWNERS

Home owners should increase the sqft_living since an increase per inch raises the value by 63.75 dollars. Lets assume theres a 1000 inch increase, theres an estimated increase in value by 63,750 dollars.

Home owners should also increase the number of bedroms,have a basement,have a waterfront, improve condition to very good,add additional floors and improve the grade to high quality in order to maximise value of their homes before listing.