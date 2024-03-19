<h3>Pump Shutdown Prediction using LSTM</h3>

<h4>Overview</h4>
This notebook demonstrates the application of Long Short-Term Memory (LSTM) neural networks to predict whether a pump may be shut down (broken) for a period of time based on input signals from sensors. The goal is to correlate sensor parameters to the pump's operating state, which can be either shutdown (0), normal operation (1), or recovering (0.5).

<h4>Data</h4>
The dataset contains sensor parameters (sensors 00 to 51) and the corresponding pump operating state. The dataset is used to train the LSTM model to predict the pump's operating state based on sensor inputs.

<h4>Model</h4>
The LSTM model is used to analyze the correlation between input sensor parameters and the pump's operating state. The model aims to identify the most important parameters for accurate prediction while minimizing the number of input parameters.

<h4>Results</h4>
The notebook will analyze the correlation between input sensor parameters and determine the most important parameters for predicting the pump's operating state. The model's performance will be evaluated to ensure accurate prediction results.
