# Lab 4 – Working with Amazon Elastic Block Store (EBS)

## Author

* **Name**: JAYANI N
* **Register Number**: 212224100025
* **Date of Submission**: 27-02-2026

---

## Objective

The objective of this experiment is to understand how Amazon Elastic Block Store (EBS) provides persistent block-level storage for EC2 instances. This lab focuses on creating and attaching an EBS volume, formatting and mounting it on an EC2 instance, storing data, and verifying data persistence after instance reboot.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing EC2 instance (Amazon Linux 2 preferred)
* Basic knowledge of Linux commands

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Amazon EBS
* SSH Client (Terminal / PuTTY)

---

## Tasks Performed

### Task 1: Explore Amazon EBS

Explore the Amazon EBS service through the EC2 dashboard. Observe different volume types such as General Purpose SSD (gp2/gp3), Provisioned IOPS SSD, Throughput Optimized HDD, and Cold HDD.

---

### Task 2: Create an EBS Volume

Create a new EBS volume in the same Availability Zone as the EC2 instance. Choose an appropriate size and volume type.

---

### Task 3: Attach EBS Volume to EC2 Instance

Attach the created EBS volume to the running EC2 instance as an additional block device.

---

### Task 4: Format the EBS Volume

Connect to the EC2 instance using SSH and format the attached volume with a file system (for example, ext4).

---

### Task 5: Mount the EBS Volume

Mount the formatted volume to a directory in the EC2 instance (for example, /data or /mnt/ebs).

---

### Task 6: Store Data in EBS Volume

Create files and directories inside the mounted EBS volume and store sample data.

---

### Task 7: Verify Data Persistence

Reboot the EC2 instance and verify that the data stored in the EBS volume is still available after reboot.

---

## Workflow (Student Explanation)

(Write the steps you followed in your own words)

1. ebs volume created
2. Volume linked to ec2 instance
3. Mounted data to volume
4. Created snapshot
5. Restored it from the snapshot

---



## Output Screenshots (Attach 3)

### Screenshot 1: EBS Volume Created

<img width="903" height="777" alt="Screenshot 2026-02-27 184016" src="https://github.com/user-attachments/assets/4c9bc89e-a4d8-4046-bba1-b2dadab163fd" />


---

### Screenshot 2: EBS Volume Attached to EC2

<img width="699" height="802" alt="Screenshot 2026-02-27 184005" src="https://github.com/user-attachments/assets/ad371b0a-f218-42ba-9bb3-52ea5f7d2382" />


---

### Screenshot 3: Mounted Volume with Data

<img width="925" height="773" alt="Screenshot 2026-02-27 183956" src="https://github.com/user-attachments/assets/79065881-c512-47f5-8248-0d734c5e9e6f" />


---

## Result / Conclusion

This experiment demonstrated how Amazon EBS provides persistent storage for EC2 instances. By creating, attaching, formatting, and mounting an EBS volume, and by verifying data after reboot, the concept of durable block storage in the cloud was clearly understood.
