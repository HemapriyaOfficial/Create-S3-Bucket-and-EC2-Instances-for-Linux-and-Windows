# CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS

## AIM
To Create S3 bucket and EC2 Instances for Linux and Windows.
    
## PROBLEM STATEMENT
This experiment aims to demonstrate the creation of an Amazon S3 bucket for storage purposes and the setup of EC2 instances for both Linux and Windows operating systems using AWS. Amazon S3 (Simple Storage Service) provides secure and scalable object storage, while EC2 (Elastic Compute Cloud) allows users to deploy virtual servers for computation and application hosting.

## ALGORITHM
### Steps 1:
## Login to AWS Management Console:
   1.Open the AWS Management Console.
   2.Navigate to the S3 service for bucket creation and EC2 for instance setup.

### Steps 2:
Create an S3 Bucket:
   1.Go to the S3 service.
   2.Click on Create bucket.
   3.Provide a unique Bucket Name and select the Region.
   4.Configure additional settings as per requirements and click Create bucket.
 
### Steps 3:
Launch EC2 Instance (Linux):
   1.Go to the EC2 service.
   2.Click Launch Instance.
   3.Select an Amazon Machine Image (AMI), such as Amazon Linux 2.
   4.Choose an Instance Type (e.g., t2.micro).
   5.Configure instance settings, key pair, and security groups, then Launch the instance.

### Steps 4:
Launch EC2 Instance (Windows):
    1.Repeat the EC2 launch steps but select a Windows Server AMI.
    2.Complete instance configuration and Launch.

### Steps 5:
Connect to Instances:

   1.Linux Instance: Use SSH to connect.
```
ssh -i "key_pair.pem" ec2-user@<linux_public_dns>
```

## COMMANDS

## S3 Bucket Creation
1.AWS CLI Command:
aws s3 mb s3:// --region

## EC2 Instance (Linux) Commands
Launch Linux EC2 instance and set up SSH access.

## EC2 Instance (Windows) Commands
Launch Windows EC2 instance and connect using RDP.


## OUTPUT

### REG NUMBER: 212223040066
### NAME: HEMAPRIYA K

## S3 BUCKET
![WhatsApp Image 2024-08-30 at 11 19 13_8eb29c49](https://github.com/user-attachments/assets/b02f48c5-0980-4c1f-a283-c116826bf5f1)
![image](https://github.com/user-attachments/assets/264794c8-04b2-4138-9f6e-fe23f1f7155b)
![image](https://github.com/user-attachments/assets/4e9fe183-a9b9-468c-a27b-674108c11846)

## EC2 INSTANCE
![WhatsApp Image 2024-08-30 at 11 10 56_35ca1bf0](https://github.com/user-attachments/assets/d357d7fc-3942-4b0a-beec-55793916f6f1)
![WhatsApp Image 2024-08-30 at 11 35 29_03d22e06](https://github.com/user-attachments/assets/d5d637d7-b162-4868-8d1e-24ec1668a4f6)
![WhatsApp Image 2024-08-30 at 10 47 53_f471aeff](https://github.com/user-attachments/assets/7ab98610-83b6-4904-9c8c-695b430fc59f)


 

## RESULT

The experiment to create an S3 bucket and launch EC2 instances for Linux and Windows is successfully completed.


 

  


