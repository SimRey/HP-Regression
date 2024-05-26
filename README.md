# House Price Prediction Project

## Overview
This project aims to predict house prices using machine learning techniques. The dataset used in this project contains categorical and continuous data such as the number of bedrooms, bathrooms, size of the house, location, etc. 

## Notebook Structure
The notebook is divided into four main parts:

1. **Exploratory Data Analysis (EDA):** This section explores the dataset thoroughly. It includes data visualization techniques to understand the distribution of features, relationships between variables, data transformation and identifying patterns in the data.

2. **Model and Data Loaders:** Here, the machine learning model is developed. This involves data preprocessing steps, feature engineering if necessary, and creating data loaders to feed the data into the model. 

3. **Training:** The model is trained using the training dataset. This section includes model initialization, loss function selection, optimization, and model evaluation during the training process. 

4. **Testing and Kaggle Submission:** The trained model is tested on the test dataset to evaluate its performance. Additionally, code for preparing the Kaggle submission is included in this section.

## Model
The model used for house price prediction is a Tabular (ideal to handle categorical and continuous data) fully connected PyTorch neural network. 

## Results
After training the model, the following results were obtained:
- Root Mean Squared Error (RMSE): 38102.668
- R-squared (R²): 84.1%
