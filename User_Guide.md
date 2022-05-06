# User Guide

## General Reminder

Please note that you are responsible for the cost of the AWS services used while running this solution. See the Cost section for more details. For full details, see the pricing webpage for each AWS service you will be using in this solution.

We attached the AdministratorAccess Policy to an IAM role when it is necessary. In most real world scenarios this is not an appropriate practice. If you have certain concern, please set up the corresponding IAM role at your discretion. For further reference, please visit this guideline

## Step 0

If you doesn’t have an AWS account yet: please go to [this website](Amazon Web Services (AWS) - Cloud Computing Services), click the button on the upright corner to create a new AWS account.
If you doesn’t know what is Amazon Forecast: please go through this tutorial and set up boto3 accordingly.
If your aws account is subscribing the free tier price plan: you may need to request an increase in quota for a more powerful instance (ml.c4.xlarge in this case).
please follow this guideline to request a quota increase.
