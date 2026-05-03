# 🚀 CI/CD Pipeline with GitHub Actions & Docker

## 📌 Project Overview

This project demonstrates a basic CI/CD pipeline using GitHub Actions to build and deploy a Dockerized static website.

## 🛠️ Tech Stack

* HTML, CSS
* Docker
* GitHub Actions

## ⚙️ Features

* Automated Docker image build
* Containerized deployment using Nginx
* CI/CD pipeline triggered on push

## 🐳 Docker Commands

```bash
docker build -t devops-website .
docker run -d -p 8080:80 devops-website
```

## 🔄 CI/CD Workflow

* Push code to GitHub
* GitHub Actions builds Docker image
* Runs container for testing

## 🌐 Access Application

http://localhost:8080

## 📈 Future Improvements

* Push image to Docker Hub
* Deploy on AWS EC2
* Add custom domain & HTTPS

---

💡 This project is part of my DevOps learning journey.
