# VPC Setup Guide

This guide walks you through creating a custom Virtual Private Cloud (VPC) with public and private EC2 instances on AWS. Below are the key steps and their corresponding diagrams/screenshots.

---

## 1. Design the Architecture

![Design the Architecture](VPC-SETUP-IMAGES/word/media/image1.png)

---

## 2. Create a VPC

![Create a VPC](VPC-SETUP-IMAGES/word/media/image2.png)
![Create an Internet Gateway](VPC-SETUP-IMAGES/word/media/image3.png)
---

## 3. Create an Internet Gateway (IGW)

![Create Public and Private Subnets](VPC-SETUP-IMAGES/word/media/image4.png)
![Create Route Tables](VPC-SETUP-IMAGES/word/media/image5.png)
![Edit Route Table for Internet Access](VPC-SETUP-IMAGES/word/media/image6.png)

![Launch EC2 in Public Subnet](VPC-SETUP-IMAGES/word/media/image7.png)
---

## 4. Create Public and Private Subnets

![Launch EC2 in Private Subnet](VPC-SETUP-IMAGES/word/media/image8.png)

![Diagram 9](VPC-SETUP-IMAGES/word/media/image9.png)

---

## 5. Create Route Tables
![Diagram 10](VPC-SETUP-IMAGES/word/media/image10.png)


---

## 6. Edit Route Table for Internet Access
![Diagram 11](VPC-SETUP-IMAGES/word/media/image11.png)
![Diagram 12](VPC-SETUP-IMAGES/word/media/image12.png)
![Diagram 13](VPC-SETUP-IMAGES/word/media/image13.png)
![Diagram 14](VPC-SETUP-IMAGES/word/media/image14.png)

---

## 7. Launch EC2 in Public Subnet

![Diagram 15](VPC-SETUP-IMAGES/word/media/image15.png)
![Diagram 16](VPC-SETUP-IMAGES/word/media/image16.png)

---

## 8. Launch EC2 in Private Subnet

Similar to case 7, but with private subnet.

---

## 9. Connect to EC2 via ssh
![Diagram 17](VPC-SETUP-IMAGES/word/media/image17.png)


---

> **Note:** All images above were extracted from the original Word document. If you need the full context or step-by-step instructions, please refer to the original `VPC-Setup.docx` file. 