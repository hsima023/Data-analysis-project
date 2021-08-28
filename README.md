# final-project-HansSolo
final-project-HansSolo created by GitHub Classroom

On this project, data analysis are being performed on ADA/BTC and ADA/USD pairs. 
Steps for the data analysis are as followed:

1. Data Mining - It is being done in files ending in data_retriever. This file make API calls and export the return values into csv files when succesful.
2. Data Preparation - It is being done in files ending in analysis. This file checks for any null values and prepare the datasets for EDA.
3. Data Visualization - It is being done to check for any hints provided by the datasets that can be used for model building in the later steps.
4. Model Building - Creating and testing for the best suited models for the datasets. Linear regression model, KNN model, and Ensemble model with voting regressor are being made. Model with the least negative MSE value and the highest R-squared error score is being picked.
5. Model Evaluation - Using the best suited models to create predictions.

The CSV files containing the datasets are in the datasets.zip in src/ directory. 
Warning: The .zip file is 67.63 MB. One of the dataset(ADAUSD) contains 5103641 rows of trade details from 2021-07-01 to 2021-08-23 taken from Kraken API.
