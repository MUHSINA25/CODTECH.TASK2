# CODTECH.TASK2
# Simple Linear Regression Model

**COMPANY**: CODTECT IT SOLUTIONS

**NAME**:MUHSINA CT

**INTERN ID**:CT08FAA

**DOMAIN**:DATA SCIENCE

**BATCH DURATION**:20 DECEMBER 2024 TO 20 JANUARY 2025


This project demonstrates the implementation of a simple linear regression model to predict a continuous target variable, specifically the closing price of gold. The dataset is split into training and testing sets, and the model is evaluated using metrics like Mean Squared Error (MSE) and R-squared (R²).

## Steps:
1. **Preprocessing**: 
   - Remove unnecessary columns and handle missing values.
   
2. **Feature Selection**: 
   - Independent variables: SP500 close, NASDAQ close, Gold open, Gold high, Gold low.
   - Target variable: Gold close.

3. **Model Building**: 
   - Train a simple linear regression model using the training data.

4. **Evaluation**: 
   - Evaluate model performance using MSE and R².

5. **Visualization**:
   - Plot actual vs predicted values to assess model accuracy.
   - Show a regression line for better interpretability.

## Results:

- **Mean Squared Error (MSE)**: 0.144  
  The MSE is relatively low, indicating that the model's predictions are quite close to the actual values. In general, the lower the MSE, the better the model's predictions.

- **R-squared (R²)**: 0.9999  
  An R² value close to 1 indicates that the model explains almost all the variability in the data. In this case, the model is performing excellently, capturing 99.99% of the variance in the target variable.

- **Model Analysis**:
  - There is a strong linear correlation between predicted and actual values, with points closely following the ideal fit line.
  - The model shows high prediction accuracy across the entire price range (100-240) with minimal scatter and no systematic errors.
  - Small residuals indicate reliable forecasting performance.
  - The model maintains consistent accuracy throughout all price levels.

Overall, the model demonstrates excellent predictive capability.

## Requirements:
- Python 3.x
- `sklearn`
- `matplotlib`
- `pandas`
- `numpy`
