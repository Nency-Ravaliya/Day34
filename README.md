# Step-by-Step Deployment Guide for Multi-Tier Web Application on Amazon ECS

This guide provides step-by-step instructions for deploying a multi-tier web application on AWS using Amazon ECS and Terraform. The deployment uses Fargate, without a Load Balancer or API Gateway, and includes configuring VPC, security groups, IAM roles, and auto-scaling.

## Prerequisites
- AWS account with IAM permissions to create resources.
- Terraform installed on your local machine.
- AWS CLI configured with your credentials.
- A Git repository containing the necessary Terraform configuration files.

## Table of Contents
- [Step 1: Clone the Repository](#step-1-clone-the-repository)
- [Step 2: Initialize Terraform](#step-2-initialize-terraform)
- [Step 3: Review and Modify Configuration](#step-3-review-and-modify-configuration)
- [Step 4: Deploy the Infrastructure](#step-4-deploy-the-infrastructure)
- [Step 5: Verify the Deployment](#step-5-verify-the-deployment)
- [Step 6: Clean Up Resources](#step-6-clean-up-resources)

---

## Step 1: Clone the Repository

First, clone the repository containing the Terraform files to your local machine:

```bash
git clone https://github.com/your-repo-name.git
cd your-repo-name/terraform
```

# Output

![image](https://github.com/user-attachments/assets/46f54bfb-1ae2-4e85-8dd2-e1f0856ff841)
![image](https://github.com/user-attachments/assets/4be58eeb-fd89-4a92-9660-276cc45ac607)
![image](https://github.com/user-attachments/assets/0f4388d5-6dbb-42af-a810-6e96bd760b90)
![image](https://github.com/user-attachments/assets/356d1df0-8883-4bdc-98a2-96216ab0d212)
![image](https://github.com/user-attachments/assets/fcf245c8-c6e4-403a-93a6-a42fb32324f8)
![image](https://github.com/user-attachments/assets/b9f0baf0-19b5-4739-8880-08cb904d11ed)
![image](https://github.com/user-attachments/assets/a7a7548f-9936-411e-b74f-d49d2fdb0e69)
![image](https://github.com/user-attachments/assets/23fcf7b3-36bc-4a7a-aa3f-9d66155894f4)
![image](https://github.com/user-attachments/assets/2a8eefad-159a-4bec-92ca-deb45123f75e)
![image](https://github.com/user-attachments/assets/47594395-04b1-45e6-a2f4-d73532fedb7d)
![image](https://github.com/user-attachments/assets/45edbf7d-4c03-471c-af1e-1fb08bd71e82)
![image](https://github.com/user-attachments/assets/32c63db9-0475-4299-9533-0519b0baf66f)
![image](https://github.com/user-attachments/assets/51c37425-152d-4b64-af46-8e4bf50c6977)
![image](https://github.com/user-attachments/assets/76c0fa1d-5f79-42c3-a237-ef7ccc4ba42b)
![image](https://github.com/user-attachments/assets/873ab5a0-f56d-4afe-b256-0d0603b918e4)
![image](https://github.com/user-attachments/assets/5f40e9c0-dffe-4460-809d-1d90cf515dec)
![image](https://github.com/user-attachments/assets/f96206e0-4aa9-4502-a7d1-6c2b310b67cf)
![image](https://github.com/user-attachments/assets/f1b9078b-b8b4-431d-8ff8-c6037f2b9381)
![image](https://github.com/user-attachments/assets/2ab16082-41c1-4399-ae94-4d8ac434a62a)
![image](https://github.com/user-attachments/assets/8dcff528-b52c-4b2b-be6c-738d23cc21be)
![image](https://github.com/user-attachments/assets/05a7cbba-002c-4619-9f53-41d49e344c6b)


















