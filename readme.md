# Sequential Data Analysis
Traditional Fourier analysis has been applied for decades due to their simplicity and usefulness in analyzing the cyclic behavior of the signal. Extending wavelet transform to cope with non-stationary signals. Dictionary based analysis gives up analytical format of bases, allowing for freedom. Machine learning gains much attention of community as it could handle non-linear, complex function. 

On the other hand, random walk model has been developed for year to understand highly stochastic nature of some signal, including the notable stock market.  
## Classical Model
### Autoregressive Model
#### Autocorrelation
#### Partial Autocorrelation
![Image of Setup](Classic/Autoregressive_Model/pacf.png)
####
![Image of Setup](Classic/Autoregressive_Model/model.png)
#### Wide-Sense Sationary?
## Machine Learning Based Model
### Simple RNN
#### Previous Quarter Data
Good at short-term fluctuation, yet a little off the general trend
![](Deep_Learning_Based/Simple_RNN/beer_sales_quarter_data.png)
#### Method 2
Better at Trend, less adaptive to local features
![](Deep_Learning_Based/Simple_RNN/beer_sales_quarter_data_2.png)
#### Method 3
Combine Trend Analysis and monthly cycles, yet off a little for some part  
Mean Absolute Error: 0.0058
![](Deep_Learning_Based/Simple_RNN/beer_sales_quarter_data_3.png)
#### Another Data Set - Sales by Country
![Image of Setup](Deep_Learning_Based/Simple_RNN/Growth_Prediction.png)
