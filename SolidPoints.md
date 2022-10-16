Solid points

-EBS backed instances are the only instances that can be restarted and stopped.
-Volume remaining size is not a metric of Amazon cloud watch 
-Enable Amazon Macie to store sensitive content on s3 bucket.
-Amazon aurora is a RDS scales automatically
-Amazon Neptune to create graphs that query large amount of data
-In-flight encryption- HTTPS
-SSM- parameter store to store secrets
-AWS Firewall Manager is a security management service that allows you to centrally configure and manage firewall rules across your accounts and applications in AWS Organizations.
Amazon Macie to protect sensitive data stored on S3
-Amazon Cloud watch : used to monitor your applications' performance and metrics.
-AWS CloudTrail allows you to log, continuously monitor, and retain account activity related to actions across your AWS infrastructure.
- S3 event notification allows destination: SQS standard, lambda, SNS
- Machine learning and High performance architecture (video processing , financial modelling and EDA) : Amazon FSx Lustre
  — The key phrases in the scenario are “big data processing frameworks” and “various business intelligence tools and standard SQL queries” to analyze the data. To leverage big data processing frameworks, you need to use Amazon EMR.
- Aurora can be connected to ML sageMaker and Comprehend
- Multi AZ to disaster recovery
- ElastiCache and RDS Read Replicas do indeed help with scaling reads.
  — Read Replicas will help as your analytics application can now perform queries against it, and these queries won't impact the main production RDS database.
  
-RDS Multi-AZ== helps when a disaster happens at the AZ level.
-Aurora Global Database helps in disaster recovery in multi region 
-ALBs can route traffic to different Target Groups based on URL Path, Hostname, HTTP Headers, and Query Strings.
-Storage optimized instances are designed for workloads that require high, sequential read and write access to very large data sets on local storage.
