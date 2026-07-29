# 🌐 Personal Portfolio Website

A responsive personal portfolio website built using **HTML, CSS, and JavaScript**, automatically deployed to **AWS S3** using **GitHub Actions CI/CD**.

---

## 🚀 Live Demo

🔗 Live Website Link:
https://niteshnk16.github.io/Personal-Portfolio/

---

## 📖 Project Overview

This project showcases my personal portfolio, skills, projects, and contact information.

The deployment process is fully automated using **GitHub Actions**. Whenever changes are pushed to the `main` branch, GitHub Actions automatically uploads the latest version of the website to an AWS S3 bucket.

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript
- Git
- GitHub
- GitHub Actions
- AWS S3 (Static Website Hosting)

---

## ⚙️ CI/CD Workflow

```
VS Code
     │
     ▼
GitHub Repository
     │
     ▼
GitHub Actions
     │
     ▼
AWS S3 Bucket
     │
     ▼
Live Portfolio Website
```

---

## 📂 Repository Structure

```
.
├── .github/
│   └── workflows/
│       └── deploy.yml
├── images/
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## ✨ Features

- Responsive Design
- Clean UI
- AWS S3 Static Website Hosting
- Automated Deployment using GitHub Actions
- Easy to maintain and update

---

## 📸 Project Screenshots

### 🏠 Portfolio Home

(Add Screenshot)

---

### ⚙️ GitHub Actions Workflow

(Add Screenshot)

---

### ☁️ AWS S3 Deployment

(Add Screenshot)

---

### 🌍 Live Website

(Add Screenshot)

---

## 🔄 GitHub Actions Workflow

Whenever code is pushed to the **main** branch:

- Repository Checkout
- Configure AWS Credentials
- Upload files to AWS S3
- Automatically Deploy Latest Version

Workflow File:

```
.github/workflows/deploy.yml
```

---

## 📌 Future Improvements

- Add CloudFront CDN
- Configure Custom Domain
- Add HTTPS using ACM
- Deploy using Infrastructure as Code (Terraform)

---

## 👨‍💻 Author

**Nitesh Kumar**

GitHub:
https://github.com/Niteshnk16

LinkedIn:
(Add Your LinkedIn)

---
⭐ If you like this project, don't forget to star the repository.
