# Kaggle New York City Taxi Fare Prediction
 
LightGBM logistic Regression model in Python to predict the taxi fares for New York City cab rides

## Dataset
The training and testing dataset can be found at https://www.kaggle.com/c/new-york-city-taxi-fare-prediction

## Project Structure
* The `NYC Taxi Fare Analysis.ipynb` performs data analysis on the first 6 million records from training dataset and adds more features to the dataset to improve model accuracy
* The `NYC Taxi Fare Prediction.ipynb` uses the new training dataset and trains on it using a LightGBM regression model

## Results
* The model trained on 6 million rows of data achieved a root mean square error (RMSE) of 3.4710, compared to the baseline RMSE of 9.6003
* Received a score of 3.01038 on the Kaggle submission 
