# 🚀 AWS DevOps Engineer Intern Assignment

## 👨‍💻 Candidate Information

* **Name:** Yogesh Madhukar Vanjari
* **Role:** AWS & DevOps Engineer Intern
* **Location:** Chhatrapati Sambhajinagar, Maharashtra, India
* **GitHub:** https://github.com/Mr-Yogesh01/Devops-intern-Assignmen
* **Date:** 10/July 2026

---

# 📌 Assignment Objective

The objective of this assignment is to demonstrate practical knowledge of AWS Cloud, Linux administration, Nginx web server deployment, Git, GitHub, and Docker by creating and managing a cloud-based web application on an AWS EC2 instance.

---

# 🛠️ Technologies Used

* Amazon Web Services (AWS)
* EC2 (Elastic Compute Cloud)
* Amzon Linux Server
* Linux Commands
* Nginx Web Server
* HTML5,CSS & Javascript
* Git & GitHub
* Docker

---

# 📋 Task 1: Launch AWS EC2 Instance

### Configuration

* Instance Name: `devops-intern-assignment`
* Operating System: Ubuntu Server 22.04 LTS
* Instance Type: `t2.micro`
* Security Group:

  * SSH (Port 22)
  * HTTP (Port 80)

  # 🚀 AWS DevOps Engineer Intern Assignment (Amazon Linux Commands Only)

## Connect to EC2

```text
chmod 400 devops-key.pem
ssh -i "devops-key.pem" ec2-user@ 3.84.26.95
```

---

## Update Server

```text
sudo yum update -y
```

---

## Install Nginx

### Amazon Linux 2023

```text
sudo dnf install nginx -y
```

### Amazon Linux 2

```text
sudo amazon-linux-extras install nginx1 -y
```

---

## Start and Enable Nginx

```text
sudo systemctl start nginx
sudo systemctl enable nginx
sudo systemctl status nginx
sudo systemctl restart nginx
```

---

## Linux Commands

```text
df -h
free -h
ps aux
top
```

---

## Deploy Static Website

```text
cd /usr/share/nginx/html
sudo vi index.html
sudo systemctl restart nginx
```

Open in browser:

```text
http:// 3.84.26.95
```

---

## Install Git

```text
sudo yum install git -y
git --version
```

---

## Git Commands

```text
git init
git add .
git commit -m "Initial commit: AWS EC2 Nginx Website Deployment"
git branch -M main
git remote add origin https://github.com/Mr-Yogesh01/Devops-intern-Assignmen
git push -u origin main
```

---

## Install Docker (Amazon Linux 2023)

```text
sudo dnf install docker -y
sudo systemctl start docker
sudo systemctl enable docker
sudo docker run hello-world
```

---

## Install Docker (Amazon Linux 2)

```text
sudo amazon-linux-extras install docker -y
sudo systemctl start docker
sudo systemctl enable docker
sudo docker run hello-world
```


