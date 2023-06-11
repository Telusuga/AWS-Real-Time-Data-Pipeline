# AWS-Real-Time-Data-Pipeline
This repository contains the code for for real time data pipeline which will take data from a csv file and load it into S3 and the data analysis is done on AWS Athena


I had used Time.csv as data in which to move from local to S3.
I had used Confluent Kafka for producer and consumer.

Producer.ipynb is the Kafka Producer Code.

Consumer.ipynb is the Kafka Consumer Code.

kafkaconsumer01--> This is the S3 bucket that I had used to push the files.

