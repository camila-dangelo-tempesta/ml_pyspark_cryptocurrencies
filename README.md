# **Apache Spark: Forecasting Bitcoin Cryptocurrency Quote**

## Predicting Bitcoin Cryptocurrency Quote in Real Time with PySpark and Machine Learning

Bitcoin is the oldest and most well-known cryptocurrency, first released as open source in 2009 by the anonymous Satoshi Nakamoto.
Bitcoin serves as a decentralized medium of digital exchange, with transactions verified and recorded on a distributed public ledger (the Blockchain) without the need for a record-keeping authority or central intermediary.
Transaction blocks contain a SHA-256 cryptographic hash of previous transaction blocks and are therefore "chained" together, serving as an immutable record of all transactions that have ever taken place.

<div align="center">
<p float="left">
    <img src="/images/bitcoin.jpg" width="1000" height="500"/>
</p>
</div>

***
## 1. BUSINESS PROBLEMS

In this project, the objective will be to build a Machine Learning model capable of predicting the price of cryptocurrencies. We will approach the project from the conception of the business problem to be solved to the delivery of the predictive model. We will use real publicly available data

The data is available through the link [Bitcoincharts](https://bitcoincharts.com/charts/)

We will use historical Bitcoin price data from 2011 to 2021. As the year 2022 was very atypical for Bitcoin, we chose not to use data from that year.

***
## 2. BUSINESS ASSUMPTIONS

The CSV file contains data from 2011 to 2021, with OHLC (Open, High, Low, Close) records of Bitcoin price, BTC Volume and Currency Volume (in this case the dollar). The last column indicates the weighted price of Bitcoin.
The timestamps are in Unix time. Timestamps without any trades or activity have their data fields filled with NaNs. If a timestamp is missing or there are skips, it could be because Exchange was down, Exchange did not exist, or some other technical error occurred while collecting the data.
Based on historical Bitcoin price data, our model should be able to predict the Bitcoin price in real time from new input data.


Note:
* This project can be extended to any other financial instrument that has daily quote data available.
* You can include data from 2022 if you wish, as well as other types of cryptocurrencies, and retrain the Machine Learning model.

***
## 3. SOLUTION PLANNING

- [x] **STEP 01:** **Data Cleaning**
	* Treatment of Missing Values
    
- [x] **STEP 02:** **Exploratory Data Analysis**
    * Analysis of Predictive Variables
    * Target Variables Analysis
    
- [x] **STEP 03:** **Attribute Engineering**
	* Feature Selection
	* Feature Extraction    
    
- [x] **STEP 04:** **Pre-processing**
    * Standardization

- [x] **STEP 05:** **Machine Learning**
    * **Linear Regression** (Benchmark)
    * Hyperparameter Optimization

<div align="center">
<p float="left">
    <img src="/images/modelos.png" width="350" height="200"/>
</p>
</div>

WARN messages in training model_v2 indicate that the model appears unstable and may be overfitting.

We will use the **model_v1**

***
Made By **Camila D'Angelo**

- ???? I???m currently working on [DS Comuity](https://www.comunidadedatascience.com/) and [Data Science Academy](https://www.datascienceacademy.com.br/bundle/formacao-cientista-de-dados)
- ???? I???m currently learning Data Science
- ???? How to reach me:  [LinkeldIn](https://www.linkedin.com/in/camiladangelotempesta/)

***
