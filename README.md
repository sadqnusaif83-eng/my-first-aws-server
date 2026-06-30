# My First AWS Server 🚀

This is a hands-on learning project documenting my first experience deploying and managing infrastructure on AWS (Amazon Web Services).

## 📋 Project Overview

As part of my transition from traditional Network Administration into Cloud Computing, I launched and configured a live web server on AWS EC2, accessible publicly over the internet.

## 🛠️ What I Did

- Created an AWS Free Tier account
- Launched an EC2 instance (Amazon Linux 2023, t3.micro)
- Generated and secured an SSH key pair (RSA, .pem format)
- Connected to the instance remotely via the AWS Console SSH client
- Updated the system packages using `yum`
- Installed and configured Apache HTTP Server (`httpd`)
- Configured the service to start automatically on boot using `systemctl`
- Modified the EC2 Security Group to allow inbound HTTP traffic (port 80)
- Successfully served a live web page accessible via the instance's public IP

## ⚙️ Commands Used

```bash
sudo yum update -y
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
```

## 🧠 Skills Demonstrated

- AWS EC2 instance provisioning and management
- Linux system administration (Amazon Linux 2023)
- Remote server access via SSH
- Web server installation and configuration
- AWS Security Group (firewall) configuration
- Basic networking concepts applied in a cloud environment

- ## 📸 Screenshot

![Server Running](screenshot-server-running.png)

## 🎯 Background

I come from a Network Systems Administration background and am currently building cloud computing skills, working toward the **AWS Certified Solutions Architect – Associate** certification.

## 📌 Next Steps

- Deploy a custom website instead of the default Apache page
- Explore AWS S3 for static file storage
- Learn Infrastructure as Code using Terraform
- Continue studying for the AWS SAA-C03 certification exam

---

*This project is part of my ongoing learning journey into Cloud Computing and DevOps.*


