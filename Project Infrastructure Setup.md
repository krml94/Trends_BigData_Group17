# Project Infrastructure Setup
## On AWS:
### Step 1:
Create an S3 bucket where you can upload the time series data set. https://docs.aws.amazon.com/AmazonS3/latest/userguide/create-bucket-overview.html
### Step 2:
Connect your S3 bucket to Amazon Forecast to train your time series model and generate forecasts. https://docs.aws.amazon.com/forecast/latest/dg/gs-console.html
## On Python:
### Step 3:
Run an ARIMA model in Python to generate time series forecasts. https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/
## Comparing Results:
### Step 4:
Having completed models both in Amazon Forecast and manually through Python, we can now compare the models' performance in terms of speed and error rates.
