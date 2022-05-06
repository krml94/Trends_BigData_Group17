# Trends_BigData_Group17
# AI-Driven time-series dataset forecasting based on AWS Forecast 
Trends Marketplace project for MSBA6330 Big Data Analytics by group 17 in the year 2022

Group members: Krishnamoorthy Ramanath, Shravan Panneer, Francesca Rivera, Ye Yang, Xuanyu Zhang

This project repository is created in partial fulfillment of the requirements for the Big Data Analytics course offered by the Master of Science in Business Analytics program at the Carlson School of Management, University of Minnesota

## Abstract: 
These days, it is very common for an organization to depend on predictive models to solve a few of their business challenges. Among all of those predictions, forecasting time-series data is one of the most important parts. It is used frequently at the core many industries, applied through demand forecasting, inventory management, etc. However, building predictive models, tuning those models and improving model performance can be complicated and time-consuming. 

In this project we will introduce a time-saving, high-efficiency and user-friendly tool that is used to predict time-series dataset : Amazon Forecast. We will use a dataset that meets both volume and velocity aspects of big data to introduce this tool, this compared with the performance of models built by ourselves potentially on a subset of this same dataset. We will then show the comparative advantages of this tool.

## Dataset:
Time Series Household electricity usage

Three columns are inclulded in our dataset, the first column is the Timestamp, with unit be 1 hour, from 1/1/2014 1:00 AM to 1/1/2015 12:00 AM, the second clumn is the electricity usage in that hour, the third column is the household number, the total nuumber of households is 370.

The link of our tried dataset: [docs.aws.amazon.com/zh_cn/forecast/latest/dg/samples/electricityusagedata.zip](https://docs.aws.amazon.con/zh_cn/forecast/latest/dg/samples/electricityusagedata.zip)

## Video
Link to our presentation introduction Video - https://youtu.be/VUiDEhUMl3c

## Files

[User_Guide.md](https://github.com/krml94/Trends_BigData_Group17/blob/main/User_Guide.md)

Introduction step by step on how to use Amazon Forecast and Amazon S3

[Electricity_Usage_Forecast.ipynb](https://github.com/krml94/Trends_BigData_Group17/blob/main/Electricity_Usage_Forecast.ipynb)

How to make the Time Series Forecast (Model: ARIMA) in python Jupyter Notebook

[Forecasting with Amazon Forecast.pdf](https://github.com/krml94/Trends_BigData_Group17/blob/main/Forecasting%20with%20Amazon%20Forecast.pdf)

Slides of our presentation on Amazon Forecast Introduction

[Trends Marketplace Team 17 Flyer.pdf](https://github.com/krml94/Trends_BigData_Group17/blob/main/Trends%20Marketplace%20Team%2017%20Flyer.pdf)

Flyer of Amazon Forecast, including what it is , how it performs and its advantages
