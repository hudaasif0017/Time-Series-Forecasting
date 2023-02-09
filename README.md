**Data Set :**
USD_PKR historical Data.csv was used provided
Goal : forecast the Dollar rates of future using previous data. 

**Requirements :**
We trained NNs that take 5 previous time stamps as an input and forecasts the next timestamp as an output. 
Following models were used to report and compare the results: 
  1. Simple NN
  2. RNN
  3. LSTM

RMSE was used as evaluation matric to test our predictions

**Observation:**
Increase in efficiency was reported by the use of RNN and LSTM.
Simple NN is not a good approach for time series forcasting. RNN and LSTM are highly suitable whereas LSTM is appreciated more for this.

Results of MSE are,
  1. Simple NN  40
  2. RNN        0.79
  3. LSTM       0.048
