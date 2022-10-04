# ML_Models_for_categorical_Data

# **Machine learning Models**



> **We are developing and training 4 models that are:**

1.   Linear Regression
2.   SVR (Support Vector Regressor)
3.   XGBoost Regressor
4.   Random Forest

Decision tree based models (here, XGBoost Regressor and Random forest) do not require feature scaling to be performed as they are not sensitive to the the variance in the data. Whereas, Linear regression and SVR need scalar standard.

> **We are evaluating our model on vaidation dataset (x_val, y_val) by using 3 performance metrics that are:**

1.   R square, R^2: R square is the Coefficient of determination.

     **Formula**

                R^2 = 1 - SSR/SST

   where:
   
   - SSR = sum of squares of residuals,
  
   - SST = total sum of squares

   R-square value ranges from 0 to 1, 1 means model performance is best and 0 means model performance is worst.

2.  Mean Absolute Percentage Error (MAPE): MAPE is used to measure the forecasting accuracy of a model.

    **Formula**
       
        MAPE = (1/n) * Σ(|actual – forecast| / |actual|) * 100

   where:

  - Σ = a fancy symbol that means “sum”
  - n = sample size
  - actual = the actual data value
  - forecast = the forecasted data value

  MAPE value ranges from 0 to infinity in percentage, where the lower the value the more accurate the predictions are, like 0% - 5% is the best value and around 10% is very good value.

3.  Accuracy: Accuracy is how close or far is the measurements of predictions or observations are to their actual values.

    **Formula**

                Accuracy = 100% - ER
                ER = |Observed Value - Actual Value|/Actual Value × 100.

   where:
   
   - ER = Error Rate,
   
   Accuracy value ranges from 0% to 100%, 100% means model performance is best and 0% means model performance is worst.

**We also calculated the intercept of the model and the parameters on which the model has been trained for Linear Regression and SVR model. Calculated  the coefficients of Linear Regression the model as coefficients are only available when using a linear kernel.**
