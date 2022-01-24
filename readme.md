This is the supplementary page for paper "Predicting River Water Height using Deep Learning-based Features"
# Exploratory Data Analysis
### Missing Values Visualisation
![Alt text](/check_missingvalues.png?raw=true "Check_missingvalues")

This is no missing value in the sample data

### Correlation
![Alt text](/correlation.png?raw=true "correlation")

Water height has a positive correlation with cumulative rain, while cumulative rain has a positive correlation with both instantaneous rain and water height.

### Data Distribution
![Alt text](/data_distribution.png?raw=true "data_distribution")

All data are right skewed

# Sample data of rainfall (a) and river water height (b)

<img src="/fig2a.jpg" width=100%>
<p align="center">
(a) Cumulative rainfall and instantaneous over time
</p>

<img src="/fig2b.jpg" width=94%>
<p align="center">
(b) River water height over time 
</p>

# Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), Root Mean Square Error (RMSE)

![Alt text](/errorrate_.png?raw=true "errorrate_")

# Sample actual and predicted value with the test input data

### 12 hours predicted water heights compared with their actual values given 12 hours of historical data

<p align="center">
  <img src="/rnn12hr_pred_12hr.gif" width=80%></p>
  <p align="center">
(a) LSTM


<p align="center">
  <img src="/rbf_rnn12hr_pred_12hr.gif" width=80%></p>
  <p align="center">
(a) LSTM with SVR using RBF kernel
</p>

# Training and testing losses

