File is dumped in s3 bucket from Kafka

How to export data from s3 to Redshift?

We have done the implementation of exporting data from s3 to Redshift
Steps:
1. Reading data from s3 using Pyspark
2. Do required transformation on dataset
3. Dump data to Redshift using pyspark

Dump s3 file to Redshift

![S3 Redshift](../diagrams/s3-redshift.png)



```
Install requirements.txt
```
pip install -r requirements.txt
```


```
