# Full-Stack Series

![full stack mern app](https://user-images.githubusercontent.com/70439799/218651720-d3090266-615e-493a-be9f-0e612620c04a.gif)

- Part 1 - [Let's build and deploy a full stack MERN web application](https://blog.itsrakesh.co/lets-build-and-deploy-a-full-stack-mern-web-application)
- Part 2 - [Adding Authentication to full stack MERN web application](https://blog.itsrakesh.co/adding-authentication-to-full-stack-mern-web-application)
- Part 3 - [How to write tests in full-stack MERN web application](https://blog.itsrakesh.co/how-to-write-tests-in-full-stack-mern-web-application)
- Part 4 - [Dockerizing Your MERN Stack App: A Step-by-Step Guide](https://blog.itsrakesh.co/dockerizing-your-mern-stack-app-a-step-by-step-guide)
- Part 5 - [Automate MERN App Deployment with GitHub Actions CI/CD](https://blog.itsrakesh.co/automate-mern-app-deployment-with-github-actions-cicd)
- Part 6 - [Deploying a MERN App to AWS Elastic Beanstalk with CI/CD](https://blog.itsrakesh.co/deploying-a-mern-app-to-aws-elastic-beanstalk-with-cicd)

# 🚀 Full Stack Productivity App — 3-Tier Architecture



![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)




![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)




![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)




![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)




![AWS](https://img.shields.io/badge/AWS_Elastic_Beanstalk-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)




![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)



## 📌 Overview

A **Full Stack Productivity Application** built with a **3-Tier Architecture** — Frontend, Backend, and Nginx Reverse Proxy — all containerized with **Docker Compose** and deployed to **AWS Elastic Beanstalk** using a fully automated **CI/CD pipeline with GitHub Actions**.

---

## 🏗️ 3-Tier Architecture

| Tier | Technology | Purpose |
|------|-----------|---------|
| **Frontend (Tier 1)** | React.js | User interface — what users see and interact with |
| **Backend (Tier 2)** | Node.js / Express | Business logic — handles API requests and responses |
| **Reverse Proxy** | Nginx | Routes traffic from frontend to backend efficiently |

---

## ⚙️ How It Works
---

## 🗂️ Project Structure

| File/Folder | Purpose |
|-------------|---------|
| `client/` | React.js frontend application |
| `server/` | Node.js Express backend API |
| `nginx/` | Nginx config for reverse proxy routing |
| `.github/workflows/` | GitHub Actions CI/CD pipeline |
| `docker-compose.yml` | Production multi-container setup |
| `docker-compose.dev.yml` | Development multi-container setup |

---

## 🔄 CI/CD Pipeline
---

## 🚀 How to Run Locally

### Prerequisites
- Docker and Docker Compose installed
- Node.js installed

### Step 1 — Clone the Repository
```bash
git clone https://github.com/mahi8867/productivity-app.git
cd productivity-app
docker-compose -f docker-compose.dev.yml up --build
docker-compose up --build
http://localhost
# Build and start all containers
docker-compose up --build

# Run in background
docker-compose up -d

# Stop all containers
docker-compose down

# View running containers
docker ps

# View logs
docker-compose logs -f
