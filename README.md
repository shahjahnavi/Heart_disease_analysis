# Heart Disease Prediction using Logistic Regression and Pipeline

This repository contains code for predicting heart disease using logistic regression and pipeline methods. The dataset used for this project is the UCI Heart Disease dataset.


![Data Set](https://github.com/shahjahnavi/Heart_disease_analysis/assets/138523298/4a3547c5-d95a-4870-b9e7-d145e9914ff4)


## Data Preprocessing

The data preprocessing steps include:
1. Importing the dataset using pandas
2. Checking for missing values and data types
3. Encoding categorical variables
4. Standardizing numerical variables

![Correlation HeatMap](https://github.com/shahjahnavi/Heart_disease_analysis/assets/138523298/4a906243-b8ee-4807-a58d-dcb46fe2e402)



## Model Training

Two models are trained for predicting heart disease:
1. Logistic Regression: A standard logistic regression model is trained using the 'make_pipeline' function.
2. Logistic Regression with Pipeline: A logistic regression model is trained using a pipeline that includes a standard scaler for feature scaling.

## Model Evaluation

The accuracy of each model is evaluated using the 'accuracy_score' function. Classification reports are also generated to provide a more detailed evaluation of the models' performance.

## Results

The logistic regression model achieves an accuracy of 84.85%. The logistic regression model with pipeline achieves an accuracy of 86.11%.

![Accuracy](https://github.com/shahjahnavi/Heart_disease_analysis/assets/138523298/06fb18a2-73f3-4b3a-9476-6b1f473f141f)


## Conclusion

The results suggest that both logistic regression and pipeline methods are effective for predicting heart disease. The pipeline method achieves slightly higher accuracy, indicating that feature scaling can improve the performance of the model.

## Dependencies

The code requires the following Python libraries:

1. pandas
2. numpy
3. matplotlib
4. plotly
5. seaborn
6. scikit-learn
7. keras

## Usage

To run the code, save it as a Python file and execute it using a Python interpreter. The code will output the accuracy scores and classification reports for both models.
