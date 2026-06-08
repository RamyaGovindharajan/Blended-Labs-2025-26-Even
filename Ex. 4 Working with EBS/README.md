# Lab 4 – Working with Amazon Elastic Block Store (EBS)

## Author
* **Name**: Ramya G
* **Register Number**: 212224220078
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

## Output 

### Screenshot 1: EBS Volume Created

<img width="593" height="607" alt="image" src="https://github.com/user-attachments/assets/2c69b365-dbf7-483b-8ce1-1ffc106c581e" />

---

### Screenshot 2: EBS Volume Attached to EC2

<img width="1919" height="1029" alt="Screenshot 2026-02-27 172622" src="https://github.com/user-attachments/assets/ddb7602a-a68d-412d-8a83-62c0a1f7542f" />
<img width="1919" height="807" alt="Screenshot 2026-02-27 175202" src="https://github.com/user-attachments/assets/6c115ad9-53ef-46c4-8f51-cea91598e9f4" />
<img width="1919" height="806" alt="Screenshot 2026-02-27 175217" src="https://github.com/user-attachments/assets/5d815992-d70d-41a4-8138-d6d2f308ab56" />

---

### Screenshot 3: Mounted Volume with Data

<img width="1918" height="1039" alt="Screenshot 2026-02-27 174352" src="https://github.com/user-attachments/assets/b6302d99-e3fb-48df-8ba8-4554b69cf666" />
<img width="1908" height="1032" alt="Screenshot 2026-02-27 174834" src="https://github.com/user-attachments/assets/36bea19d-73ee-47b3-bd4d-3558e835f600" />

---

## Result / Conclusion

This experiment demonstrated how Amazon EBS provides persistent storage for EC2 instances. By creating, attaching, formatting, and mounting an EBS volume, and by verifying data after reboot, the concept of durable block storage in the cloud was clearly understood.
