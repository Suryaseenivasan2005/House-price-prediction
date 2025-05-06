# Smart Regression for House Price Prediction 🏡🔮

Welcome to my project repository! This project represents an in-depth exploration into the realm of regression analysis for predicting house prices. Let me take you through the complete journey I embarked on during this project.


## Overview

This project took me four days to complete from start to finish and proved to be quite challenging yet rewarding. It involved leveraging advanced regression techniques to accurately estimate house sale prices using a variety of independent features.

## Problem Definition

The primary objective was crystal clear: develop a predictive model capable of estimating house sale prices with precision. This required delving into a vast array of features and understanding their impact on the target variable.

## Data

The dataset used in this project was obtained from a Kaggle competition titled "House Prices - Advanced Regression Techniques." It consisted of several files, including training and testing datasets, a data description file, and a sample submission file. Access the dataset from the [Kaggle competition page](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data).

## Preprocessing and Feature Engineering

The journey began with carefully preparing and refining the data. I addressed missing data by excluding features with significant gaps and adopting tailored strategies to handle the remaining missing values. Instead of scaling techniques, I opted for a temporary label encoder with a data copy to identify the top features. Furthermore, I applied one-hot encoding to categorical features within the top-selected attributes.



## Model Selection and Training

After careful consideration, I opted to utilize three regression models for this project: Random Forest Regression, XGBoost, and CatBoost. These models were chosen for their robust performance and ability to handle complex datasets effectively.

The data was split into training and validation sets, and the selected models were trained using the processed data. Baseline modeling was performed to assess initial performance, followed by hyperparameter tuning to optimize model performance further.


## Model Evaluation

The models were evaluated using MAE metrics, providing insights into their predictive capabilities. Random Forest Regression emerged as the top performer, exhibiting superior accuracy in estimating house sale prices.

## Testing and Deployment

The final trained model was applied to the testing data, requiring additional preprocessing steps and adjustments to accommodate differences in the dataset. Once validated, the model was deployed using Streamlit, providing users with an intuitive interface for inputting house details and obtaining estimated sale prices.


## Conclusion

In conclusion, this project represents a comprehensive journey from data preprocessing and feature engineering to model selection, training, evaluation, and deployment. It involved overcoming various challenges and culminated in the creation of a functional predictive model and user-friendly interface for house price prediction.
By clicking this link : https://house-price-prediction-5ehdg4fbeqxyqqctcphrcf.streamlit.app/ you can test my project.
