# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: Long Short-Term Memory Recurrent Neural Network for Tidal Level Forecasting

  - **[Link](https://ieeexplore.ieee.org/abstract/document/9169644)**
  - **Objective**: Use a deep learning model to predict tidal water levels in 17 harbors in Taiwan.
  - **Methods**: A forecasting model was developed on the basis of the long short-term memory (LSTM) recurrent neural network. They used the tidal water level for 21 years from different observation stations. To varify their results they compared them with six other forecasting models in terms of the mean absolute percentage error (MAPE) and root mean square error (RMSE).
  - **Outcomes**: The developed LSTM model had the lowest forecasting error for the tidal water level for up to 30 days. The average MAPE and RMSE values for the developed model were 6.97% and 0.049 m, respectively.
  - **Relation to the Project**: Since tides depend strongly on the geographic region the transferability of their results to our project is limited, nevertheless showed their work, that neural networks easily learn periodic functions and that LSTMs are a good choice for tidal level time series prediction.

- **Source 2**: Timeseries forecasting for weather prediction

  - **[Link](https://keras.io/examples/timeseries/timeseries_weather_forecasting/)**
  - **Objective**: Predict different weather parameters using an LSTM.
  - **Methods**: They used a simple LSTM, with an input layer, one LSTM layer and an output layer. They used the Adam optimizer with a fixed learning rate of 0.001.  
  - **Outcomes**: As far as their documentation shows they only did single step predictions and unfortunately did not analyse their results further (in terms of RMSE or else), but the few expamples they ploted looked promising.
  - **Relation to the Project**: They showed a simple way to implement a LSTM model for time series prediction, which was helpful in the development of our own model implementations.

- **Source 3**: Time series forecasting

  - **[Link](https://www.tensorflow.org/tutorials/structured_data/time_series#setup)**
  - **Objective**: This source is a tutorial by TensorFlow showing an introduction to time series forecasting.
  - **Methods**: After giving a comprehensive overview of data preprocessing they show different styles of models including Convolutional and Recurrent Neural Networks (CNNs and RNNs).
  - **Outcomes**: More complex models did perform way better than the basic autoregressive model.
  - **Relation to the Project**: This was a helpful overview also in terms of data preprocessing.
