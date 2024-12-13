# Stock_Market-Forecasting of Indian Defense Companies 


This project explores the prediction of stock market prices using five distinct machine learning models: Support Vector Regressor (SVR), Linear Regression, Random Forest Regressor, Gated Recurrent Units (GRU), and Long-Short Term Memory (LSTM). The primary goal is to evaluate the effectiveness of these models in forecasting stock prices and to identify the key factors influencing stock market movements.

Objectives
 Assess the predictive power of various machine learning techniques in stock market forecasting.
 Compare the performance of different models using statistical evaluation metrics.
 Provide insights that can guide the development of new financial models or enhance existing ones.

 Methodology
 
Machine Learning Models

Linear Regression - 
A statistical approach to model the relationship between a dependent variable and one or more independent variables by minimizing errors between observed and predicted values.

Random Forest Regressor - 
An ensemble learning technique that creates multiple decision trees using random subsets of data and features, then averages their predictions for enhanced accuracy and reduced overfitting.

Support Vector Regressor (SVR) - 
A method that uses support vector machines to identify a hyperplane in high-dimensional space, minimizing prediction errors and effectively handling non-linear relationships.

Gated Recurrent Unit (GRU) - 
A type of Recurrent Neural Network (RNN) that addresses the vanishing gradient problem using gating mechanisms to retain important information over long sequences.

Long-Short Term Memory (LSTM) - 
An advanced RNN architecture designed to learn long-term dependencies in sequential data using memory cells with forget, input, and output gates.

Evaluation Metrics - 
To compare model performance, the following statistical metrics are used:

Mean Squared Error (MSE): Measures the average squared differences between predicted and actual values.
Mean Absolute Error (MAE): Quantifies the average magnitude of prediction errors.
R-squared (Coefficient of Determination): Indicates the proportion of variance in the target variable explained by the model.


Key Findings

The Gated Recurrent Unit (GRU) model demonstrated the highest predictive accuracy among all the models tested. It achieved a high R-squared value of 0.97 (BEML dataset) and 0.98 (BHEL dataset), indicating a strong correlation between predicted and actual stock prices. Additionally, it recorded significantly low error metrics, with Mean Squared Error (MSE) values of 3.6 (BEML) and 1.1 (BHEL), and Mean Absolute Error (MAE) values of 6.70 (BEML) and 1.3 (BHEL). These results highlight GRU’s capability to effectively model sequential data and accurately predict stock price fluctuations, making it a highly reliable choice for stock market forecasting.

In contrast, the Support Vector Regressor (SVR) model exhibited the poorest performance. It achieved a relatively low R-squared value of 0.78 (BEML) and 0.85 (BHEL), reflecting weaker predictive accuracy. Furthermore, it recorded significantly higher error metrics, with MSE values of 391.78 (BEML) and 23.78 (BHEL), and MAE values of 18.88 (BEML) and 3.84 (BHEL). These findings suggest that SVR struggles to handle the complexity of stock market data, making it less suitable for forecasting purposes compared to other models in the study.


GRU showed the best performance with high R-squared (0.97–0.98) and low MSE/MAE values, making it highly effective for stock price forecasting.
SVR had the poorest accuracy, with low R-squared (0.78–0.85) and high MSE/MAE values, rendering it less suitable for stock market predictions.



