# 🚀 Jenkins CI/CD Pipeline with Docker on AWS EC2

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## 📌 Project Overview
A fully automated CI/CD pipeline built with Jenkins on AWS EC2 that automatically pulls code from GitHub, builds a Docker image, tests, and deploys a Flask web application — all in under 30 seconds.

## 🏗️ Architecture
```
GitHub Push → Jenkins Pipeline → Docker Build → Deploy Container → Flask App Live
```

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| AWS EC2 (t3.micro) | Host Jenkins server |
| Jenkins | CI/CD automation |
| Docker | Containerization |
| Python Flask | Web application |
| GitHub | Source code management |

## 📋 Pipeline Stages
1. **Clone Repo** — pulls latest code from GitHub
2. **Build Docker Image** — builds Flask app image
3. **Test** — runs automated tests
4. **Deploy** — stops old container, runs new one on port 5000

## ✅ Results
- Pipeline completes in **under 30 seconds**
- Flask app live at `http://<EC2-IP>:5000`
- Zero manual deployment effort

## 👨‍💻 Author
**Prasanth S** — Cloud & DevOps Engineer
- GitHub: [prasanth17-cloud](https://github.com/prasanth17-cloud)
- Email: prasanthprasanthleo@gmail.com
