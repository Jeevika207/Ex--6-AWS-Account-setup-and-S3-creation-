# CLOUD STORAGE CREATION AND LAUNCHING AN (EC2) INSTANCE IN AWS
## NAME: Jeevika R
## REG NO: 212224040137
## Aim

To launch, configure, monitor, resize, and manage an Amazon EC2 instance in AWS, configure its security group to host a web server, and explore instance protection and service quotas.

---

## Algorithm / Steps

1.Start the AWS lab and open the AWS Management Console.

2.Navigate to the EC2 service and ensure the N. Virginia (us-east-1) region is selected.

3.Click Launch Instance and enter the instance name as Web Server.

4.Select the default Amazon Linux 2023 AMI and choose the t2.micro instance type.

5.Select the vockey key pair.

6.Configure the network by selecting Lab VPC and PublicSubnet1.

7.Create a new security group named Web Server security group and remove the default inbound rule.

8.Keep the default 8 GiB EBS storage.

9.Enable Termination Protection.

10.Paste the provided User Data script to automatically install and start the Apache web server.

11.Launch the EC2 instance and wait until its status changes to Running with 2/2 status checks passed.

12.Monitor the instance using the Status Checks, Monitoring, System Log, and Instance Screenshot options.

13.Copy the instance's Public IPv4 Address and attempt to access the web page.

14.Modify the security group's inbound rules by allowing HTTP (Port 80) access from Anywhere-IPv4.

15.Refresh the browser and verify that the message "Hello From Your Web Server!" is displayed.

16.Stop the instance, change the instance type from t2.micro to t2.small, and increase the EBS volume size from 8 GiB to 10 GiB.

17.Enable Stop Protection, restart the instance, and verify the changes.

18.Explore EC2 Service Quotas in the AWS Service Quotas console.

19.Test Stop Protection by attempting to stop the instance, then disable the protection and stop the instance successfully.

20.Submit the lab and verify the completion score.

---

## Outputs

## Launch Amazon EC2 Instance

<img width="1918" height="1100" alt="Screenshot 2026-08-05 002435" src="https://github.com/user-attachments/assets/63eef58f-4d2b-4647-b0d8-b7347342f44f" />

## Name and tags

<img width="1915" height="1082" alt="Screenshot 2026-08-04 093627" src="https://github.com/user-attachments/assets/cab161b5-3f88-49e6-a8bd-e78f359b7d2f" />

## Instance Type

<img width="1918" height="1091" alt="Screenshot 2026-08-04 093654" src="https://github.com/user-attachments/assets/f0c24176-9352-44ca-98f3-4046786c5be9" />

## Key pair (login)
<img width="1917" height="997" alt="Screenshot 2026-08-04 093809" src="https://github.com/user-attachments/assets/7d468596-5dc6-4693-870f-a8a8c1281bdb" />

## Network settings
<img width="1918" height="995" alt="Screenshot 2026-08-04 094024" src="https://github.com/user-attachments/assets/51485c77-77db-439e-8ace-ee28192ed1b5" />

## Configure storage
<img width="1918" height="996" alt="Screenshot 2026-08-04 094339" src="https://github.com/user-attachments/assets/e6433b0d-7699-4346-90df-5884b2d2c0bf" />

## User data
<img width="1918" height="992" alt="Screenshot 2026-08-04 094515" src="https://github.com/user-attachments/assets/be2ccb2a-1144-4204-9420-150b1f301127" />

## Status checks
<img width="1918" height="983" alt="Screenshot 2026-08-04 234856" src="https://github.com/user-attachments/assets/cfb65a45-ffa5-421e-b831-58fdef03815a" />

## Get System log
<img width="1918" height="987" alt="Screenshot 2026-08-04 234705" src="https://github.com/user-attachments/assets/0f33a00d-756c-4e81-b1b0-bbcfabc10b6b" />

<img width="1918" height="996" alt="Screenshot 2026-08-04 234545" src="https://github.com/user-attachments/assets/27b31c41-3756-47b7-8ee3-7f0b69597b39" />

### Get instance screenshot.
<img width="1918" height="987" alt="Screenshot 2026-08-04 234722" src="https://github.com/user-attachments/assets/7c8f5294-0d57-4fb7-ab46-97f5a0f7fbed" />

<img width="1918" height="997" alt="Screenshot 2026-08-04 234804" src="https://github.com/user-attachments/assets/bca4387b-e7f6-4bb9-8f70-c278b248d93b" />

## Copy Public IPv4 address 
<img width="1918" height="990" alt="Screenshot 2026-08-05 003941" src="https://github.com/user-attachments/assets/76cb75c4-f7fe-445a-a27b-c802b36f0164" />

## Security Groups.

<img width="1917" height="983" alt="Screenshot 2026-08-04 235307" src="https://github.com/user-attachments/assets/9f441dd1-bf7c-4126-a21a-57345ace5a38" />

## Edit Inbound rules
<img width="1915" height="985" alt="Screenshot 2026-08-04 235236" src="https://github.com/user-attachments/assets/32e91848-9c4f-4fde-bbaa-b0ce02a4962a" />

## Apache web server output
<img width="1918" height="1080" alt="Screenshot 2026-08-05 010414" src="https://github.com/user-attachments/assets/4d5f831f-fe72-422f-9975-b5973d853682" />

## Stop Instance
<img width="1920" height="1044" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/6e40ee1f-6351-4c65-8fcf-3d9f35d88e86" />

## Change Instance Type
<img width="1920" height="990" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/bb923232-dd28-45c3-9216-4110a836eb2c" />

## 
<img width="1920" height="993" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/6dc62282-2a8f-4482-ac4c-f091dca90cf3" />

## Enable stop protection
<img width="1920" height="982" alt="Screenshot (60)" src="https://github.com/user-attachments/assets/13665362-c32f-4f48-9239-8a704a21079e" />

## Resize the EBS Volume
<img width="1920" height="1200" alt="Screenshot (63)" src="https://github.com/user-attachments/assets/51cef10f-79de-4953-8308-ec4a82e5a367" />

## EC2 Instance Stopped Successfully / Lab Completion
<img width="1920" height="1200" alt="Screenshot (67)" src="https://github.com/user-attachments/assets/56bda470-e6be-47ad-abe8-c67795e92300" />



## Result

An Amazon EC2 instance was successfully launched, monitored, secured using security groups, resized by changing the instance type and EBS volume, protected using termination and stop protection features, and managed successfully in the AWS Management Console.
