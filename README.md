## PySpark Linear Regression Analysis Project
### Objective:
The aim of this project was to implement a Linear Regression model using PySpark to predict Salary based on various input features. The project involved data preprocessing, training a linear regression model, and evaluating its performance.
### 1. Data Preprocessing:
VectorAssembler: The dataset had multiple feature columns (such as years of experience, education level, etc.). VectorAssembler was used to combine these individual features into a single Features vector, which is required as input for the Linear Regression model.
### 2. Data Splitting:
The dataset was split into training data (80%) and testing data (20%). This split allows the model to be trained on one subset and tested on a separate subset to evaluate its predictive performance.
### 3. Model Training:
Linear Regression Model: The Linear Regression algorithm was trained using the training dataset. This model aims to predict the Salary based on the input features by finding the best-fit line that minimizes the error between the predicted and actual values.
### 4. Model Prediction and Evaluation:
After training, the model was used to make predictions on the test data.
##### Model Evaluation Metrics:
a. Root Mean Squared Error (RMSE): The RMSE value was calculated to measure the prediction error, which came out to be 5358.32. This indicates how far the predicted salaries are, on average, from the actual salaries.
b. R-Squared (R²): The model’s R² value was 0.9683, meaning approximately 96.83% of the variance in the salary data was explained by the model.
c. Adjusted R-Squared (Adjusted R²): The Adjusted R² value was 0.9672, which adjusts for the number of features used in the model, providing a more accurate measure of model fit.
### 5. Results:
The linear regression model demonstrated excellent performance with an R² of 0.9683, indicating a high degree of accuracy in predicting salary.
The Adjusted R² of 0.9672 confirms that the model is highly effective, even after accounting for the number of input features.
The RMSE value of 5358.32 shows the average deviation between predicted and actual salaries, which is relatively low and indicates a good fit.
