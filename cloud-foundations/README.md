# ☁️ EC2 SSH + Linux Commands Lab

## 🎯 Objective
Learn how to securely connect to an AWS EC2 instance using SSH and practice basic Linux commands.  
Set up a web server and explore cloud infrastructure hands-on.

---

## ⚙️ Environment
- **Cloud Platform:** AWS  
- **Instance Type:** t3.micro (Free Tier)  
- **AMI:** Red Hat Enterprise Linux  
- **Connection Method:** SSH using PEM key  

---

## 🪜 Steps Performed

### 1️⃣ Adjust Key Permissions
```bash
chmod 400 ayo-key.pem
```
### 2️⃣ Connect to EC2 Instance via SSH
```bash
ssh -i ayo-key.pem EC2-user@<EC2-Public-IP>
```
### 3️⃣ Practice Basic Linux Commands

### 4️⃣ Install Apache Web Server
```bash
sudo yum update
sudo yum install apache2 -y
sudo systemctl start apache2
sudo systemctl enable apache2
```

🧠 Lessons Learned

- How to SSH into an EC2 instance securely

- Basic Linux navigation and file management

- Installing and running services (Apache)

- Understanding security groups and open ports



