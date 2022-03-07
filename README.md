# [Ubiquant Market Prediction](https://www.kaggle.com/c/ubiquant-market-prediction/overview)
This repo is the collective work of [DSI DARLM](team) for module 2 of the [DSI Africa, 2022](http://dsi-program.com/). 

![stocks](https://miro.medium.com/max/1200/1*8f224aUuj_sZqIYx6KEymw.jpeg)
 
## About the Challenge


Artificial intelligence is shaping the future of stock trading and has removed some of the guess work out of this high risk business. And while some hedge funds are relucatant to fully automate the process, many rely on AI powered algorithms to shape their decision making.

In this kaggle challenge, hosted by [Ubiquant Investment (Beijing) Co., Ltd](https://www.kaggle.com/c/ubiquant-market-prediction/overview), the goal was to build a model that forecasts an investment's return rate. Ubiquant Investment relies on international talents in math and computer science along with cutting-edge technology to drive quantitative financial market investment. This challenge offers an opportunity for the team to delve in time-series analysis, forecasting and optimisation.

Intrestingly, the dataet provided contains obfuscated data, providing an extra layer of diffidulty for the data scientist who has to derive all pertinet information from a keen study of the dataset itself.

#### Model Performance Evaluation

This challenge was evaluated on the mean of the [Pearson Correlation Coefficient](https://www.investopedia.com/terms/c/correlationcoefficient.asp) on the time_id.



## Contents
* [Model Overview](model_overview)
* [Technologies](technologies)
* [Notebook](notebook)
* [Resources and References](resources)
* [Team](team)

## Model Overview

A bagging ensemble of four deep neural networks including an LSTM model. The predictions from each model are average by taking a mean and this is the final prediction.

![Model](https://github.com/DhasiM/module2/blob/main/Module%202%20Model%20Pipeline.png)

## Resources

We read and referenced a number of resources. Here's a few;
#### EDA
* [Time Series data exploration with pandas](https://ourcodingclub.github.io/tutorials/pandas-time-series/)
* [Time series data](https://www.earthdatascience.org/courses/earth-analytics/time-series-data/summarize-time-series-by-month-in-r/)

#### Time Series Modelling
* [How to Select Model for Time Series](https://neptune.ai/blog/select-model-for-time-series-prediction-task)
* [Time Series Forcasting](https://neptune.ai/blog/time-series-forecasting)

## Team
* [Rhodasi](https://github.com/DhasiM)
* [Lali Ali](https://github.com/laliali20)
* [Arnold](https://github.com/arnold402)
* [Marcelina](https://github.com/MarcelinaKinyumu)
* [Dennies](https://github.com/denniesbor)


