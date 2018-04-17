#  Predicting Oil Prices Using an RNN with Watson Studio 

## Part 1 - Building and running the model

Researchers have found  that recurrent neural networks (RNN) with LSTM can outperform traditional forecasting models like ARIMA when  forecasting future values of certain  time series data. (For an example see [A comparison of artificial neural network and time series models for forecasting commodity prices](https://www.sciencedirect.com/science/article/pii/0925231295000208))

This Watson Studio lab  will demonstrate how to apply an RNN with LSTM to forecast weekly West Texas crude oil prices. The data used to train the model covers the time period  from 01/03/1986 to 3/30/2018. The data  was downloaded from the [Federal Reserve Bank of St. Louis](https://fred.stlouisfed.org)

##  Setup

### 1 Sign up for Watson Studio 

If you are not already signed up for Watson Studio, [sign up here](https://www.ibm.com/cloud/watson-studio)

### 2 Create a Watson Studio Project 

2.1 From the Watson Studio home page click on **New Project**
![New Project](images/ss1.png)


2.2 Select a **Jupyter Notebook** project type and click **OK**
![Jupyter Notebook](images/ss2.png)

2.3 Name the project *Time Series RNN Demo* and click **Create**

### 3. Create  and run this lab's notebook

3.1 Click on the **Assets** tab 
![Assets](images/ss3.png)

3.2 Scroll down to the *Notebooks* section and click on **New Notebook**

3.3 Name the Notebook *My Time Series RNN Demo* . Select **From URL** and copy the following URL into the **Notebook URL** field

```https://raw.githubusercontent.com/djccarew/timeseries-rnn-lab-part1/master/oilpricernn.ipynb```

![Create Notebook](images/ss4.png)

3.4 Click on **Create Notebook**. After a few seconds the notebook should be loaded
![Notebook loaded](images/ss5.png)

3.5 Follow the instructions in the notebook to complete the exercise. 