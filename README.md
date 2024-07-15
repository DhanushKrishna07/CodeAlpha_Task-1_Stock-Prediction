This is task 2 of CodeAlpha | Data Science Domain.

Take stock price of any company you want and predicts
its price by using LSTM. Use only Jupyter notebook
code.

 💱Stock Prediction💸 
 
In this project, I explored the power of Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) models to forecast Tesla's stock prices. By leveraging historical stock data, I successfully implemented and compared these advanced deep learning techniques to predict future prices.

Project Highlights:

•Utilized time series data for predicting stock prices using advanced deep learning techniques.
•Successfully implemented and compared two different neural network architectures: Simple RNN and LSTM.
•Demonstrated the importance of data normalization and feature scaling in improving model performance.
•Showcased the process of hyperparameter tuning and model evaluation through visualization techniques.
•Provided insights into the strengths and limitations of RNN and LSTM models in time series forecasting.

Steps Involved:

•Imported essential libraries for data manipulation, visualization, and machine learning.
•Loaded the Tesla stock dataset and performed initial data exploration.
•Split the dataset into training and validation sets.
•Created the training dataset by extracting the 'Open' column and converting it into an array.
•Applied normalization to scale the dataset values between 0 and 1.
•Created input sequences (X_train) and corresponding output values (y_train) from the training data.
•Built and trained a Simple RNN model, including adding layers and dropout regularization.
•Evaluated the RNN model by plotting loss and accuracy over epochs and visualizing predictions against actual values.
•Created the test dataset from the validation split and prepared it for evaluation.
•Evaluated the RNN model's predictions on the validation data and visualized the results.
•Built and trained an LSTM model to compare its performance against the Simple RNN model.
•Evaluated the LSTM model by plotting loss and accuracy over epochs and visualizing predictions against actual values.
•Predicted the future stock price for the next day using both the Simple RNN and LSTM models based on the last 50 days of data.

Key Takeaway:

This project demonstrates the effectiveness of RNN and LSTM models in predicting Tesla stock prices. Key steps include data preprocessing, model training, hyperparameter tuning, and visualization. The LSTM model showed superior performance, highlighting the importance of capturing long-term dependencies in time series forecasting.
