# AWS-Real-Time-Data-Pipeline
This repository contains the code for for real time data pipeline which will take data from a csv file and load it into S3 and the data analysis is done on AWS Athena


I had used Time.csv as data in which to move from local to S3.
I had used Confluent Kafka for producer and consumer.

Producer.ipynb is the Kafka Producer Code.

Consumer.ipynb is the Kafka Consumer Code.

kafkaconsumer01--> This is the S3 bucket that I had used to push the files.

![Untitled Jam 1](https://github.com/Telusuga/AWS-Real-Time-Data-Pipeline/assets/113308141/521bd287-713a-449c-a737-447fe8e90313)


When the consumer runs the files will be loaded into S3 Bucket
![image](https://github.com/Telusuga/AWS-Real-Time-Data-Pipeline/assets/113308141/da6f8394-754b-4ea7-a86b-6076b2dda2c5)

After the files load now the crawler run has been completed which will be creating a metadata in the Data Catalog
![image](https://github.com/Telusuga/AWS-Real-Time-Data-Pipeline/assets/113308141/84f7a2ee-9a56-4806-8b7a-a28fd56ddd5a)

After the Crawler run the data can be viewd in AWS Athena
![image](https://github.com/Telusuga/AWS-Real-Time-Data-Pipeline/assets/113308141/600072f1-6633-4a86-b9d2-9f03bd3f3efe)
