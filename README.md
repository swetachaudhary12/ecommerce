## E-commerce Multiple Linear Regression - MATLAB Project

This MATLAB project performs multiple linear regression on E-commerce data to analyze the relationship between several independent variables (x1, x2, x3, x4) and a dependent variable (y). The dataset is imported from a CSV file, and the model fits the equation y = c1 + c2*x1 + c3*x2 + c4*x3 + c5*x4, where c1 to c5 are the coefficients.

### Steps:
1. Data Import: The dataset is read from the CSV file "Ecom.csv" and processed into MATLAB variables.
2. Model Fitting: Using the method of least squares, the best-fit coefficients are computed to establish the linear regression model.
3. Absolute Error Calculation: The absolute error is determined by comparing the true values of y with the predicted values obtained from the regression model.
4. Evaluation Metric: The mean absolute error is calculated to assess the accuracy of the model's predictions.

### Usage:
1. Ensure you have MATLAB installed on your system.
2. Download the "Ecom.csv" dataset and place it in the MATLAB working directory.
3. Open the MATLAB script and run the code to perform the linear regression and evaluate the model's accuracy.

This project is a valuable tool for data analysts and researchers aiming to explore the relationships between various factors in E-commerce and predict the outcome variable (y) based on the given independent variables (x1, x2, x3, x4). The provided absolute error and mean absolute error offer crucial insights into the model's performance and its ability to make accurate predictions in an E-commerce context.
