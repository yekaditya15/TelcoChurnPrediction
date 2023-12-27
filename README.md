

# Telecom Customer Churn Prediction

This project focuses on predicting customer churn in the telecom industry using a deep learning model. Customer churn is a critical metric for businesses, and understanding the factors that lead to it can aid in strategic decision-making.

## Overview

The provided Jupyter notebook (`teleco-chun-prediction.ipynb`) walks through the entire process, from data loading to model evaluation. Here's a brief overview of the key steps:

1. **Data Loading and Exploration:**
   - The dataset (`WA_Fn-UseC_-Telco-Customer-Churn.csv`) is loaded, and a quick exploration of the data is conducted.
   - The `customerID` column, deemed unnecessary, is dropped.

2. **Data Cleaning:**
   - The `TotalCharges` column, which should be of type float, is identified as an object. It is converted to numeric values after handling blank strings.

3. **Data Visualization:**
   - Visualizations are used to understand the distribution of features, such as tenure and monthly charges, in relation to customer churn.

4. **Data Preprocessing:**
   - Various preprocessing steps, including handling 'No internet service' and 'No phone service' values, converting binary columns to 1s and 0s, and one-hot encoding categorical columns, are performed.

5. **Model Building (ANN):**
   - A neural network model is constructed using TensorFlow/Keras.
   - The model is trained on the preprocessed data, and its performance is evaluated.

6. **Model Evaluation:**
   - The notebook includes confusion matrix and classification report analyses to assess the model's precision, recall, and overall accuracy.

7. **Conclusion:**
   - The notebook concludes with insights into model performance and recommendations for further refinement.



Feel free to contribute or open issues if you have suggestions or improvements!

