# Serverless File Compression Project

#### This project implements a serverless file compression solution on AWS. Files uploaded to an Amazon S3 bucket are automatically compressed using AWS Lambda and stored back in S3. The solution is event-driven, cost-effective, and requires no server management.

## Features

- Fully serverless architecture

- Automatic file compression on upload

- Supports multiple file types

- Cost-efficient and scalable

- Secure and event-driven

## Step-by-Step Implementation

### Step-1:Create one S3 bucket

![](./pictures/3.png)

### Step-2: Create a Lambda Function

![](./pictures/1.png)


### Step-3:Write the Lambda function to compress uploaded files

![](./pictures/2.png)

### Step-4:Configure S3 event notifications

![](./pictures/4.png)

### Step-5: Add Trigger to Lambda Function

![](./pictures/5.png)

### Step-6:Upload a file to the input bucket and Verify the compressed file appears in the same bucket

![](./pictures/6.png)

- SNS notify success notification after file compression

## Conclusion

This serverless file compression project demonstrates how AWS services can be combined to create an efficient, scalable, and automated solution without managing servers. It is ideal for data pipelines, storage optimization, and cost reduction use cases.

