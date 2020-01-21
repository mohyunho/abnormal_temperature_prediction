# Task Description
Create time series random temperature data with condition label and predict future condition of temperature with ML algorithms

In this self-tutirial, the time series data of temperature is manually generated. 
A proper temperature (normal condition) is set to 17~23°C, and below 17°C and over 23°C are considered as abnormal (cold/hot) respectively.

The sampling period of the temperature is '1 minute'. The time delta of Resampling is '10 minutes'. And, the window sizes of rolling window calculations are '30 minutes' and '1 hour'. 

Statistical features in time domaion:(max, min, mean, std, var, median), and two additional features (skew, kurt) for only 30, 60 minutes.
Labels(normal / abnormal_cold / abnormal_hot) are costructed with lag features for every hour so that ML classifier computes the probability that the temperature changes in to the hot/cold state in the next 1 hour.

