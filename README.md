# Stock Prices Forecasting
This project aims to develop, evaluate, and compare autoregressive, gradient boosting, and neural networks algorithms on forecasting using stock market data, incorporating sentiment analysis from social media as exogenous data.The objective is to analyze the effectiveness of advance data analytics techniques in conjunction with Big Data processing.

The selected companies for the experiment are: AAPL, AMZN, NFLX, NVDIA, and TSLA.

The project is divided into two Jupyter notebooks.

Part 1:

Focuses on Big Data techniques, including the use of HDFS, MySQL, and NoSQL databases; exploratory data analysis; sentiment analysis; and big data streaming techniques utilizing the PySpark language.

Part 2:

Covers advanced data analytics, such as the development and application of autoregressive, gradient boosting, and neural network models; sentiment analysis; and the incorporation of an interactive dashboard.

# Introduction
Stock prediction has been a topic of interest among both analysts and researchers for a long time. Forecasting of stock market prices is a challenging process due to their high volatile nature and the influence of numerous factors such as economic conditions, political events, leadership changes, and social media activity.

Predicting stock prices based on either historical data or textual information alone has proven to be insufficient. Gupta & Chen (2020) in their study on sentiment analysis for stock price prediction, found that there is a strong correlation between the movement of stock prices and the publication of news articles. 

This project aims to develop, evaluate and compare autoregressive, gradient boosting, and neural networks algorithms for stock prices forecasting, incorporating sentiment analysis from social media as exogenous data. 

The selected models are: SARIMAX (Seasonal AutoRegressive Integrated Moving Average with Exogenous regressors), XGBoost (Extreme Gradient Boosting), LSTM (Long Short-Term Memory), GRU (Gated Recurrent Units), and Facebook Prophet. 

The experiment utilized stock data from AAPL, AMZN, NFLIX, NVDA, and TSLA, along with exogenous data obtained from tweet sentiment analysis. The datasets were stored using both SQL and NoSQL databases.

All the models previously mentioned were hyperparameters tuned in order to optimize their performance. 

Forecasted values were compared against actual data using statistical evaluation metrics. Additionally, each model was used to predict stock prices up to 7 days ahead and presented through an interactive dashboard.
# Apache Hadoop
Apache Hadoop was utilized for storage the datasets. It is an open-source software framework designed for the distributed storage and allows to process large datasets across clusters. Hadoop Distributed File System (HDFS) was used to manage storage, enabling efficient handling of big data (Judge, 2012). Additionally, Yet Another Resource Negotiator (YARN), was employed to manage computing resources. YARN allows multiple data processing engines like interactive SQL, real-time streaming and batch processing to run and process data stored in HDFS (Murthy, 2014).

<img width="844" height="377" alt="image" src="https://github.com/eriostre/Stock-Market-Forecasting-Using-Twitter-as-Exogenous-Data/blob/main/images/Picture1.png" />

