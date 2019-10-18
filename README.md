## Predictive Analysis of Cryptocurrency Price Using Deep Learning

The decentralization of cryptocurrencies has
greatly reduced the level of central control over them, impacting
international relations and trade. Further, wide fluctuations in
cryptocurrency price indicate an urgent need for an accurate
way to forecast this price. This paper proposes a novel method
to predict cryptocurrency price by considering various factors
such as market cap, volume, circulating supply, and maximum
supply based on deep learning techniques such as the recurrent
neural network (RNN), Gated Recurrent Unit (GRU), Convolution1D and the long short-term memory (LSTM),which are
effective learning models for training data, with the LSTM
being better at recognizing longer-term associations. The pro-
posed approach is implemented in Python and validated for
benchmark datasets.

### Files
#### Data Ananlysis
1. btcoin_Correlation.ipynb
2. btcoin_Correlation_analysis.ipynb 
#### Neural network models
1. bitcoinlarge.ipynb - This file is the paper implementaion of LSTM on USD large bitcoin dataset of kaggle
2. bitcoinsmall.ipynb - This file is the paper implementaion of LSTM on USD small bitcoin dataset of kaggle
3. compare_LSTM_GRU_CONV1D.ipynb - Comparison of LSTM, GRU and CONV1D on bitcoin dataset
4. comparewithtimesteplargew_l.ipynb - Comparison of error with change in timestep on 25000000 data
5. comparewithtimestepsmallw_l.ipynb - Comparison of error with change in timestep on 12000000 data
6. comparewithvaryhiddenstep.ipynb - Comparison of error with change in hidden units of LSTM
7. performance_on_various_crytocurrency.ipynb	 - Performance of LSTM on price prediction of various crytocurrencies
8. tweet_bitcoin.ipynb - Performce of bitcoin price prediction on incorporating twitter sentiment regarding bitcoin

### Data
This folder contains various crytocurrency dataset extracted from coinmarket

### Model
Various model that was built and saved for bitcoin prediction

### Bitcoin dataset link
[Bitcoin dataset](https://www.kaggle.com/mczielinski/bitcoin-historical-data)
