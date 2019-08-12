# Air_Pollution_Forecastion_LSTM_Keras
In this repository, we use a deep LSTM algorithm using Keras to forecast air pollution in Beijing. This study is based on 2018 KDD CUP and the meteorological and air quality data can be downloaded from KDD CUP of Fresh Air https://biendata.com/competition/kdd_2018/.

Four layers of Long Short-Term Memory (*LSTM*) layers are employed. Data are available at Air pollution forecasting using LSTM algorithm in Keras


Four Long Short-Term Memory (*LSTM*) layers are used and after each *LSTM* layer a *Dropout* layer with value of 0.2 is used to avoid overfitting.
For each *LSTM* layer, 144 sequence (previous time step) is considered. This means we predict the air pollution hourly using the data of 6 last days (6 days * 24 hours = 144 hours).

![GitHub Logo](/Architecture.png)


