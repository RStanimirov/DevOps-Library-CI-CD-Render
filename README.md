# SoftUni Students Library – CI/CD Pipeline Demo

A full-stack Node.js application demonstrating a complete **CI/CD workflow** using **GitHub Actions** and deployment on **Render**.

This project is built for educational purposes as part of DevOps/CI-CD training.

🔗 Live Demo: https://devops-library-ci-cd-render-fe.onrender.com

---

## Tech Stack

### Frontend
- HTML / CSS / JavaScript
- Lit HTML
- Page.js (routing)

### Backend
- Node.js
- Express.js

### Testing
- Playwright (UI testing)

### CI/CD
- GitHub Actions

<img width="1178" height="211" alt="actions-build-test-deploy" src="https://github.com/user-attachments/assets/fe7cdf71-f25f-4677-9178-cbbe30eeca23" />

### Deployment
- Render (Frontend + Backend)


## ⚠️ Disclaimer

This project is created for educational purposes only.  
It is not intended for production use and comes without any guarantees or warranties.

---

## Steps for running locally, upload in github, buld, test and deploy in Render:

1. Open repo locally, buld it, run the server (frontend and backend) and test it (NB- playwright ):
- npm install
- npm install -D @playwright/test
- npx playwright install
- npm run start
- npm run server
- npm run test

---

## Git workflow

- git init
- git add .
- git commit -m "Initial commit"
- git branch -M main- 
- git remote add origin <your-repo-url>
- git push -u origin main

---

## ☁️ Deployment (Render)

This project uses two Render services:

1. Backend (Web Service)
Runs Node.js/Express server
Entry point: server/server.js

3. Frontend (Static Site)
Serves frontend application (index.html)
Build path: root (./)
