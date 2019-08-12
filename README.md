# Air_Pollution_forecastion_LSTM_Keras
Air pollution forecasting using LSTM algorithm in Keras
In this repository we use a deep LSTM algorithm to forecast air pollution. Four layers of Long Short-Term Memory (LSTM) layers are employed. Data are available at 

https://biendata.com/competition/kdd_2018/ 

Four *LSTM* layers are used and after each *LSTM* layer a *Dropout* layer with value of 0.2 is used to avoid overfitting.
For the *LSTM* layer 144 sequence (previous time step) is considered. This means we keep the data for 6 last days (6 days * 24 hours).

![GitHub Logo](/Architecture.png)

