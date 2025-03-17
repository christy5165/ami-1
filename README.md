# ami-1
Automated EC2 Instance Backingup using AMI
# Automated EC2 Instance Backup using AMI

   This project automates the backup of EC2 instances using Amazon Machine Images (AMIs). It includes a Python script to create AMIs and delete old backups, and can be scheduled using AWS Lambda and CloudWatch.

   ## Features
   - Create AMIs for EC2 instances.
   - Delete old AMIs based on retention days.
   - Automated scheduling using AWS Lambda.

   ## Requirements
   - Python 3.x
   - Boto3 library
   - AWS CLI

   ## Setup
   1. Clone this repository.
   2. Configure AWS credentials using aws configure.
   3. Deploy the Lambda function and schedule it using CloudWatch.

   ## License
   This project is licensed under the MIT License.
