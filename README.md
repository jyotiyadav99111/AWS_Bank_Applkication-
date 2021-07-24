# AWS_Bank_Application
A demonstration of how a model can be deployed in AWS. The example dataset chosen over here is related to bank products and target variable depicts if the customers buy it or not

The code defines the way in which any model can be deployed over the AWS for production purpose. Each and every instruction has been proided in the sheet.

Please follow the following steps to create the instance in AWS:

1. Create AWS Account (No money required)
2. Login into AWS Management console
3. Search for AWS Sagemaker
4. Left hand side panel navigation --> Notebook > Notebook Instances > Create Notebook Instances
5. Create IAM Role while creating teh notebook instance (This is essential part of the process because it helps manage the access of the notebook)
6. The instance creation will take some time. Once done, please open it and start writing the below code


The process goes as follows:

1. Set up environment
2. Download and split dataset
3. Model
4. Deployment
5. Predictions
6. Delete endpoint


Libraries Required: 
1. Numpy
2. Pandas
3. os
4. urllib
5. sagemaker
6. boto3

The individual packages can be istalled through the command: ```pip install package_name```


Note: The demonstration is for the XGBoost model
