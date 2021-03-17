# Housing_Prices

This is a Competition for [Kaggle](https://www.kaggle.com/c/home-data-for-ml-course) Learn Users

The purpose of this challenge is to predict the sales price for each house. For each Id in the test set, we must predict the value of the Sale Price variable. 

### File descriptions
  - train.csv - the training set
  - test.csv - the test set
  - data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here
  - sample_submission.csv - a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms

### Practice Skills

  - Creative feature engineering 
  - Advanced regression techniques like random forest and gradient boosting

### Metric
- Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking  logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

### Acknowledgments

[The Ames Housing dataset](http://www.amstat.org/publications/jse/v19n3/decock.pdf) was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset. 
