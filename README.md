# univariate-time-series-machine-learning
A deep learning solution for univariate time series
Data is provided by Jason Brownlee in https://github.com/jbrownlee/Datasets
This is the assignment project for deeplearning.ai's Tensorflow Developer course on coursera.

##### I tried CNN-LSTM based deep learning model instead of ARIMA models because it yields better results
than traditional statistical methods. I also used huber loss function because it is less sensitive to outliers
and appropriate to use on time series data such as this. Data consist of minimum daily temperatures and by it's nature
it is AR(Autoregressive).

