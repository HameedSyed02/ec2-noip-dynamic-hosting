# ec2-noip-dynamic-hosting
Website hosted on an EC2 instance using No-IP dynamic DNS


# EC2-Hosted Website with No-IP Dynamic DNS

This project demonstrates how to host a web server on an AWS EC2 instance and point a free dynamic DNS domain (via No-IP) to it.

## 🌐 Live Demo
Access the live server here:  
➡️ http://yourname.ddns.net

## ⚙️ Tech Stack
- **AWS EC2** – Ubuntu instance
- **httpd** – Web server
- **No-IP Free DNS** – Dynamic DNS pointing to EC2
- **Linux (Ubuntu)** – Hosting environment

## 🔧 Setup Steps

### 1. Launch EC2 Instance
- Ubuntu 22.04
- Allow HTTP (80) and HTTPS (443) in Security Group

### 2. Install httpd
- sudo apt update
- sudo apt install httpd -y

### upload a static file in ec2 instance
 - /var/www/html/<static_website>

### Lanch the instance and public IPv4 in no-ip DNS entry
![image](https://github.com/user-attachments/assets/25114720-1203-42cd-a3d7-f42bb6c2ffa9)
![image](https://github.com/user-attachments/assets/e402fc6d-65a6-4ed7-9957-335216abd3fb)
![image](https://github.com/user-attachments/assets/9599ca5b-2d56-4987-9975-fe0e109d80d2)
![image](https://github.com/user-attachments/assets/be31f5aa-c611-45d4-9919-d96e38ecfbb8)





