# Triggering-AWS-Lambda-Function-Job-using-Amazon-SQS
Problem Statement
In this assignment we will be triggering trigger a Lambda function using SQS. This Lambda function will process messages from the SQS queue and insert the message data as records into a DynamoDB table.
Solution
Create the Lambda Function
Create the SQS Trigger
Copy the Source Code into the Lambda Function and deploy (The same has been provided)
Create an EC2 instance, also create an user inside and copy the send_messages.py file and then Start sending messages to the DynamoDB table from the Messages SQS queue with an interval of 0.1 seconds
Confirm Messages Were Inserted into the DynamoDB Table
