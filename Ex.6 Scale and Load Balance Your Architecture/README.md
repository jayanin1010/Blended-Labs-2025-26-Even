# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture
Author : JAYANI N   Reg no :212224100025   Date :7/03/26

---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

Logged into the AWS Management Console and reviewed the existing EC2 architecture created in previous labs.

Created a Launch Template specifying the AMI, instance type, security group, and configuration for EC2 instances.

Created an Auto Scaling Group (ASG) using the launch template and configured minimum, desired, and maximum instance capacity.

Set up an Application Load Balancer (ALB) and created a target group to distribute incoming traffic to EC2 instances.

Attached the Auto Scaling Group to the Load Balancer target group so that new instances are automatically registered.

Configured scaling policies using Amazon CloudWatch based on CPU utilization.

Tested the architecture by generating traffic and observing automatic scaling and load balancing across instances.

---

## Output Screenshots 


<img width="921" height="893" alt="Screenshot 2026-03-07 225526" src="https://github.com/user-attachments/assets/46b76656-fdd6-4189-8e37-a3e7562cad5a" />
<img width="915" height="928" alt="Screenshot 2026-03-07 225515" src="https://github.com/user-attachments/assets/bd4d6956-0752-4081-8698-945dde5e2873" />
<img width="921" height="831" alt="Screenshot 2026-03-07 225606" src="https://github.com/user-attachments/assets/4de135aa-454b-4be6-ba20-e625fd9649b6" />



## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
