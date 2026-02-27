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
  <img width="1912" height="1199" alt="image" src="https://github.com/user-attachments/assets/478f4d2c-6a18-41b3-823d-458ab9da7c91" />
<img width="1912" height="1199" alt="image" src="https://github.com/user-attachments/assets/f82f19e9-d842-4c92-a160-44c8d6e59df0" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
<img width="1919" height="1109" alt="Screenshot 2026-02-27 134951" src="https://github.com/user-attachments/assets/ea4e3c60-9861-407c-87ea-85e6537aa8d2" />
<img width="1910" height="1100" alt="image" src="https://github.com/user-attachments/assets/60494e35-4b2c-40cf-bc5e-8b401756003a" />
<img width="1918" height="1199" alt="image" src="https://github.com/user-attachments/assets/f6a58d37-e204-4ec0-8200-ef459c62f953" />




### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
<img width="1919" height="1150" alt="image" src="https://github.com/user-attachments/assets/8c306e5d-ba50-44e6-b08d-84a1844d5eab" />
<img width="1910" height="1144" alt="image" src="https://github.com/user-attachments/assets/0190ca47-a666-4d73-a8a4-346cc1b638d3" />




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
**Name:** Josipha reg no:212224220044
**Course:** Introduction to Cloud Computing  

