# User Guide

## General Reminder

Please note that you are responsible for the cost of the AWS services used while running this solution. See the Cost section for more details. For full details, see the pricing webpage for each AWS service you will be using in this solution.

We attached the AdministratorAccess Policy to an IAM role when it is necessary. In most real world scenarios this is not an appropriate practice. If you have certain concern, please set up the corresponding IAM role at your discretion. For further reference, please visit this guideline

## Step 0

If you doesn’t have an AWS account yet: please go to [this website](https://aws.amazon.com/?nc1=h_ls), click the button on the upright corner to create a new AWS account.

If you doesn’t know what is Amazon Forecast: please go through this [tutorial](https://docs.aws.amazon.com/forecast/latest/dg/getting-started.html) accordingly.

## Step 1
<img width="963" alt="Screen Shot 2022-05-05 at 7 42 32 PM" src="https://user-images.githubusercontent.com/90431892/167048757-fd736022-015d-4ae3-9be7-82415f92ba21.png">

First you should upload the dataset (csv format) to Amazon [S3](https://s3.console.aws.amazon.com/s3/)

## Step 2
In this page, click the 'create dataset group'.

<img width="1825" alt="Screen Shot 2022-05-05 at 7 44 50 PM" src="https://user-images.githubusercontent.com/90431892/167048935-d178dd48-af29-4cce-82f3-d25bdc1ebb65.png">

During creating, make sure the sequence of columns in your dataset can match the sequence of attrbutes shown here. Then link your S3 bucket to this page.
<img width="1063" alt="Screen Shot 2022-05-05 at 7 45 48 PM" src="https://user-images.githubusercontent.com/90431892/167049005-fc01c7bc-7f12-4e81-b554-ea3cbc74dca9.png">

## Step3
After successfully imported, click 'Train Predictor' to train a new predictor.
<img width="1174" alt="Screen Shot 2022-05-05 at 7 48 31 PM" src="https://user-images.githubusercontent.com/90431892/167049196-c032f089-430a-4771-8b39-e97ab88d8274.png">

Choose the correct frequency (1 hour in our sample) and choose the number of units of frequency you want to predict
<img width="1217" alt="Screen Shot 2022-05-05 at 7 49 33 PM" src="https://user-images.githubusercontent.com/90431892/167049272-8240613a-badd-4c3d-ba95-37c025146408.png">

After finishing prediction, you can see all the evalution metrics here
<img width="1125" alt="Screen Shot 2022-05-05 at 7 50 44 PM" src="https://user-images.githubusercontent.com/90431892/167049349-07b5bc16-f52b-4a5d-b569-cda0aa237da0.png">

## Step 4

Here we click the 'Create a forecast' to make forecastion.
<img width="1204" alt="Screen Shot 2022-05-05 at 7 51 49 PM" src="https://user-images.githubusercontent.com/90431892/167049462-783d0c90-fa08-41d7-8ea5-6a17fdfafab8.png">

After finishing forecastion, we can click 'Query forecast' to lookup the results for each unit.
<img width="1186" alt="Screen Shot 2022-05-05 at 7 54 13 PM" src="https://user-images.githubusercontent.com/90431892/167049563-d8e22c45-a037-4e2b-8295-48c36fe20c8d.png">

And you can also export your result to your S3 bucket and download it to your local computer
<img width="1183" alt="Screen Shot 2022-05-05 at 7 54 57 PM" src="https://user-images.githubusercontent.com/90431892/167049627-92edadb3-bd86-4a9b-9be7-b9d3641044b6.png">
