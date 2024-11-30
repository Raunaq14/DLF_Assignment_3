# DLF_Assignment_3
RNN_Stock_Price_Prediction

Stock Market Prediction with RNN, LSTM, and GRU

This project explores stock market prediction using Recurrent Neural Networks (RNN), Long Short-Term Memory (LSTM), and Gated Recurrent Units (GRU). The focus is on predicting stock prices based on historical stock market data. This repo contains the implementation of three different models for stock price prediction and their evaluation.

Dataset

The dataset includes stock market prices and volumes for different companies over the years. The data is preprocessed to clean and format it for model training.

	•	Features used for prediction: Open, High, Low, Volume, Close (adjusted as necessary)
	•	Target variable: Close price


Models Implemented

	1.	RNN: A basic Recurrent Neural Network model for sequential prediction.
	2.	LSTM: A Long Short-Term Memory (LSTM) model to capture long-range dependencies.
	3.	GRU: A Gated Recurrent Unit model, a variant of LSTM with fewer parameters and faster training.

Evaluation Metrics

The models are evaluated using the following metrics:

	•	MSE (Mean Squared Error)
	•	RMSE (Root Mean Squared Error)
	•	MAE (Mean Absolute Error)
	•	R² (Coefficient of Determination)

The following results were obtained:

	•	RNN: MSE: 0.0047, RMSE: 0.0686, MAE: 0.0573, R²: 0.9848
	•	LSTM: MSE: 0.0090, RMSE: 0.0949, MAE: 0.0825, R²: 0.9709
	•	GRU: MSE: 0.0140, RMSE: 0.1181, MAE: 0.1023, R²: 0.9549

Visualizations

The training progress, model predictions, and actual stock prices are visualized for comparison, showing the model’s ability to forecast stock prices.
