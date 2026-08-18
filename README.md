# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-

#### NAME: SATHYAA R
#### REG NO: 212223100052

## Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 

## Procedure:

a)	Steps to Create a first S3 Bucket:

Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.

Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.

Step 3: Create Bucket
Click the Create bucket button.

Step 4: Configure Bucket Settings
•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.

Step 5: Object Ownership
Choose between:
	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.

Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.

Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.

Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).

Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.

Step 10: Create the Bucket. Click Create bucket at the bottom of the page.

b)	i. Steps to launch an EC2 Instance
1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).
5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

c)	Step 3: Connect to Your Instance
•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.

## Snap Shots:

Snap Shot 1: Simple Storage Service (S3)

<img width="1004" height="539" alt="491474554-e189fe45-6f13-4e8f-9731-1dc8e26809f1" src="https://github.com/user-attachments/assets/2a806003-60aa-48e5-baf3-e38172c34375" />


Snap Shot 2:  EC2 (Elastic Compute Cloud) – Instance

<img width="981" height="583" alt="491474796-a598eb61-00b0-4d60-9c77-8e888a3af2e2" src="https://github.com/user-attachments/assets/8ac5730c-76ee-4832-a23e-02a2aab6fe35" />


## Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS.
