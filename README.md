# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-

## NAME: SATHYAA R
## REG NO: 212223100052

## AIM
To Create S3 bucket and EC2 Instances for Linux and Windows.

## PROBLEM STATEMENT
This experiment demonstrates the process of setting up cloud infrastructure on AWS by creating an S3 bucket for storage and EC2 instances to host Linux and Windows environments. The goal is to provide an overview of how to configure and interact with these resources effectively, along with commands and screenshots to document the process.

## ALGORITHM
### Step 1: Log in
 
Log in to AWS Console
 
### Step 2: Create an S3 Bucket
 
Navigate to the S3 service.

Click on Create bucket.

Enter a Bucket name and select a Region.

Configure Bucket settings as required (e.g., versioning, public access).

Click on Create bucket to finalize.

### Step 3: Create an EC2 Instance (Linux)
 
Go to the EC2 service.

Click on Launch Instance.

Select an Amazon Machine Image (AMI) for Linux (e.g., Amazon Linux 2).

Choose an Instance Type (e.g., t2.micro for free tier).

Configure Instance Details, Storage, and Security Group.

Review and click Launch with a key pair (or create one if needed).

### Step 4: Create an EC2 Instance (Windows)
 
Return to the EC2 service and click Launch Instance.

Select a Windows AMI (e.g., Windows Server 2019).

Choose the Instance Type.

Configure Instance Details, Storage, and Security Group.

Review and launch with a key pair (for future login).

### Step 5: Verify and Connect to Instances
 
Verify the status of both instances in the EC2 dashboard.

Connect to the Linux instance using SSH.

Connect to the Windows instance using RDP.

## COMMANDS
Include the commands used in the Experiment.

## OUTPUT

### S3 BUCKET:

<img width="1723" height="913" alt="one" src="https://github.com/user-attachments/assets/ad900bf6-c945-462f-aa75-67201f093bd0" />

<img width="1721" height="914" alt="two" src="https://github.com/user-attachments/assets/820504e4-d5e4-4623-819f-a1a3dc2b38cf" />


### EC2 INSTANCE:

<img width="1720" height="914" alt="three" src="https://github.com/user-attachments/assets/3a1c3f60-2e7c-44e3-aa31-e53479d88bc0" />

<img width="1721" height="914" alt="four" src="https://github.com/user-attachments/assets/e1193969-8e7c-4579-ad21-b6636a54add5" />


## RESULT
Successfully created an S3 bucket and EC2 instances for both Linux and Windows, demonstrating cloud resource management on AWS.
