# House-Price-Prediction
Predicting House Prices on Favorable (and Unfavorable) Variables - Kaggle Competition

The competition link can be found at: [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview)

**Prompt:**

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price (SalePrice) of each home.

**Files provided:**

train.csv - the training set

test.csv - the test set

data_description.txt - full description of each column and what the abbreviations mean

sample_submission.csv - a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms

**Files I added**

Planning.csv - I ranked the explanatory variables (high, medium, low impact) I thought had the largest impact on SalePrice, and tested their correlation with SalePrice

Cleaning House Price Data - Cleaned out null values and got an understanding of the most correlated values and normalizing them for proper use - following example of a popular Notebook listed on the challenge

House Price Regression XGB Model - XGB Model trained on cleaned test data to output the SalePrice of the test data.
