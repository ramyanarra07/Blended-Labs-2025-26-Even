# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**  
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/1c52bbc2-9c07-441f-84d2-663909441ef1" />
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/aed9aa3e-05a9-45c3-b9ab-455a44995921" />
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/b923cf41-070e-4a31-b54a-7f0544ed8aaa" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/7882875c-cc43-4b9e-9488-7007b236d419" />
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/b4d81ed0-2854-4637-a132-580286bdef9e" />
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/475431fc-8e0f-44c5-b651-c674fde2551e" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/3cf9ab9a-89ea-4ffb-a7ec-813349227849" />
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/926a380a-ce92-4a10-a9ae-bca5966969d2" />
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/94be6f25-e6e2-46cc-8ec8-8430726cea9a" />



## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** NARRA RAMYA
**Course:** Introduction to Cloud Computing  

