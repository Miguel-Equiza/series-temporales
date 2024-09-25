# Project README: Time Series Forecasting Models for Madrid Temperature Data
![Uploading Captura de pantalla 2024-09-25 094758.png…]()

## Project Overview

In this project, we will build and compare three different forecasting models to predict the temperatures of Madrid using the dataset from [Global Climate Change Data](https://data.world/data-society/global-climate-change-data), specifically the file `GlobalLandTemperatures_GlobalLandTemperaturesByMajorCity.csv`. 

### Models to be built:
1. **Baseline Model**: Using a simple forecasting technique (such as moving average or naive forecasting) covered in the practical sessions.
2. **Machine Learning Model**: Implementing a machine learning algorithm (such as Random Forest, XGBoost, or similar) as discussed in theory and practice.
3. **Deep Learning Model**: Using a neural network architecture (such as LSTM or GRU) for time series forecasting.

## Dataset Information

The dataset used is `GlobalLandTemperatures_GlobalLandTemperaturesByMajorCity.csv`, which can be downloaded for free from the [data.world link](https://data.world/data-society/global-climate-change-data). 

We will filter the data for **Madrid** and use it to model and forecast the temperatures for this city only.

## Guidelines for the Project

### Data Preparation

1. **Load the data**: The data is loaded from the CSV file and converted into a Pandas dataframe.
2. **Filter**: We will filter the dataset to only include data for the city of Madrid.
3. **Imputation of missing values**: Handle any missing or incomplete data (if applicable).
4. **Outlier Detection**: Detect and handle any outliers present in the dataset.
5. **Train-test split**: We will split the dataset into training (80%) and validation/testing (20%) sets.

### Model Training

For each model, we will:

1. Split the data into training and validation sets.
2. Import the necessary libraries for each model.
3. Train the model using the 80% training data.
4. Apply hyperparameter tuning using techniques such as grid search (for Machine Learning and Deep Learning models).
5. Perform forecasting on the 20% validation data. The results will be stored and analyzed for comparison.

### Model Evaluation

The performance of each model will be evaluated using relevant metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and others. The final output will include:

- A **ranking** of the models based on the chosen metrics.
- A **graph** comparing the predicted values to the actual values in the validation data.

### Conclusions

A final section will provide insights and conclusions based on the results of each model. We will analyze:

- Which model performed best.
- The practical implications of the results.
- Possible improvements and further experimentation.

