# Machine Learning - Exoplanet Exploration
![image](https://user-images.githubusercontent.com/59347919/86622791-7eb0d200-bf8e-11ea-8114-e7e0119daee1.png)
# Background
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. There were 3 machine learning models created: Logistical Regression, Decision Tree, and K-Nearest Neighbor. These models were used to determine candidate exoplanets based on a series of elements from a specific dataset. The details of each model will be presented including performance accuracy associated with predictions along with comparison analysis. Prior to creating each model, the following data processing and preparation steps are required:
# Data Processing and Preparation
* Read csv file and clean up all null values
* Select features from dataset (columns of data elements)
* Define target y-values as koi_disposition and x-values as features selected from dataset columns
* Split x and y-values into train and test sets and then scale data to ensure it can handle potential outliers
# Model 1 - Logistical Regression
* Set up Logistical Regression Model
* Train Model by fitting the y-trained target values and x-trained scaled values to model
* Score Logistical Regression Model by Train and Test - Train Score: 0.786 --- Test Score: 0.815. Logistical Regression model is able to predict an exoplanet based on the features selected from the dataset () approximately 82% of the time.
* Use grid search to fine tune the parameters for the model and received a best score of 0.779 which is slightly lower than the test score value. Adjusting the C and gamma values may render a different result
# Model 2 - Decision Tree
* 
