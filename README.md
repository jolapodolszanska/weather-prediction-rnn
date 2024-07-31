# Weather Prediction Model

This repository houses a model developed to predict weather conditions specifically using Recurrent Neural Network (RNN) technology. The model features LSTM (Long Short-Term Memory) layers, which are tailored to handle the sequential nature of time-series data in weather prediction.

## Dataset
The model is trained on the "Weather Prediction" dataset, comprising time-series meteorological data.

## Model Architecture

The architecture of the model includes:

- **Input Layer**: Receives sequences with dimensions `(number of timesteps, 1 feature per timestep)`.
- **RNN Architecture (LSTM Layers)**:
  - Four LSTM layers, each with 50 units, designed to capture both short-term and long-term dependencies in the data.
  - Each LSTM layer is followed by a dropout layer, with a dropout rate of 0.2, to mitigate overfitting.
- **Output Layer**:
  - A dense layer with one unit aimed at outputting the predicted weather condition.

## Results
Explore the `results` section for detailed performance metrics and visualizations of the model's predictions, demonstrating its effectiveness in forecasting weather conditions.
<p align="center">

</p>
<p align="center">
 <img src="https://raw.githubusercontent.com/jolapodolszanska/weather-prediction-rnn/main/output.png" />
</p>

<p align="center">
 <img src="https://raw.githubusercontent.com/jolapodolszanska/weather-prediction-rnn/main/output2.png" />
</p>



