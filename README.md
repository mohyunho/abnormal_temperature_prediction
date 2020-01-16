# abnormal_temperature_prediction
Create time series random temperature data with condition label and predict future condition of temperature with ML algorithms

In this self-tutirial, the time series data of temperature is manually generated. 
A proper temperature (normal condition) is set to 18~22°C, and below 18°C and over 22°C are considered as abnormal (cold/hot) respectively.

The sampling period of the temperature is '1 minute' and prediction. The size of time window is '1hour' 
so that ML classifier computes the probability that the temperature changes in to the hot/cold state in the next 1 hour.

