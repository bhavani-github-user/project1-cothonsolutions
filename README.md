
# project1-cothonsolutions
# AWS Real-Time Data Analytics Dashboard

This project leverages AWS services to build a real-time data pipeline and dashboard:

- *Amazon Kinesis*: Captures streaming data.
- *AWS Lambda*: Processes data in real-time.
- *CloudWatch*: Monitors and logs the pipeline.
- *Amazon QuickSight*: Visualizes data through file uploads.

## Project Setup

### Prerequisites
- AWS account
- Access to Amazon Kinesis, Lambda, CloudWatch, and QuickSight

### Steps:
1. *Setup Kinesis Stream*  
   Follow the instructions in kinesis/kinesis-setup.md.

2. *Deploy Lambda Function*  
   Use the code in lambda-functions/process_data.py.

3. *Monitor with CloudWatch*  
   Refer to cloudwatch/monitoring-setup.md.

4. *Visualize in QuickSight*  
   Upload the data file (data/sample-upload-file.csv) following the instructions in quicksight/dashboard-setup.md.
