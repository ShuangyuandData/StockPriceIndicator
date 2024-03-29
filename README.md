# StockPriceIndicator
### Libraries:

1. pyramid-arima or pmdarima
2. keras
3. tensorflow


### Summary: 
Investment firms, hedge funds and even individuals have been using financial models to better understand market 
behavior and make profitable investments and trades. A wealth of information is available in the form of historical stock prices
and company performance data, suitable for machine learning algorithms to process. This project is to build a stock price predictor that 
takes daily trading data over a certain date range as input, and outputs projected estimates for given query dates. 
Note that the inputs will contain multiple metrics, such as opening price (Open), highest price the stock traded at (High), how 
many stocks were traded (Volume) and closing price adjusted for stock splits and dividends (Adjusted Close); 
the project only predicts the Adjusted Close price.

1. Predict the adjusted close price based on the multiple metrics for stocks.
2. Explore stocks of GOOG, IBM, GLD, SPY from 2010 to 2018
3. Split data into train and test data (1/5) and perform regression using Linear Regression, K-Nearest Neighbors, Auto Arima, and Long Short Term Memory.
4. Decrease RMS of the test data from over 100 to 4.

![Image of result](https://github.com/ShuangyuandData/StockPriceIndicator/blob/master/f1.png)
![Image of result](https://github.com/ShuangyuandData/StockPriceIndicator/blob/master/f2.png)
![Image of result](https://github.com/ShuangyuandData/StockPriceIndicator/blob/master/f3.png)
![Image of result](https://github.com/ShuangyuandData/StockPriceIndicator/blob/master/f4.png)

### Referece:
1. Udacity
2. https://www.analyticsvidhya.com/blog/2018/10/predicting-stock-price-machine-learningnd-deep-learning-techniques-python/
3. https://www.analyticsvidhya.com/blog/2017/06/a-comprehensive-guide-for-linear-ridge-and-lasso-regression/
4. https://www.analyticsvidhya.com/blog/2018/03/introduction-k-neighbours-algorithm-clustering/
5. https://www.analyticsvidhya.com/blog/2018/08/k-nearest-neighbor-introduction-regression-python/
6. https://www.analyticsvidhya.com/blog/2018/08/auto-arima-time-series-modeling-python-r/
7. https://www.analyticsvidhya.com/blog/2018/05/generate-accurate-forecasts-facebook-prophet-python-r/
8. https://www.analyticsvidhya.com/blog/2017/12/fundamentals-of-deep-learning-introduction-to-lstm/
