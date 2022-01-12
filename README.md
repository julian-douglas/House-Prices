# Predicting House Prices - Kaggle Competition

This notebook is my submission for the Kaggle House Prices Competition, which contains a dataset containing the the features of 1460 houses, plus their selling prices.

This notebook uses several different regression methodologies in order to predict the price of a house given its features (its area, how many bedrooms it has, the year it was built, etc). My methodology is outlined as follows:

- Load the dataset into a Pandas dataframe
- Feature selection:
  - Identify which numerical features to keep based on their correlation with the sales price
  - Identify which features to keep from those based on their correlation with each other
  - Identify which categorical features to keep
- Handle missing data
- Feature Engineering
- Data Pre-Processing:
  - One-hot encode the categorical features
  - Standardise and normalise the numerical features
- Perform different regression models on the data and compare their performance (in terms of MRSE):
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - Random Forest
  - Support Vector Machine
  - Extreme Gradient Boosting
- And finally, make the submission on the test data.
