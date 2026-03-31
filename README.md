# 🔐 Secure Pass – Premium Password Generator

A modern, secure, and fully responsive password generator web app with a premium UI/UX, built with DevOps practices including Docker and CI/CD using GitHub Actions.

---

| **Submitted by** | Anushka Singh (0201AI221018)            |
|------------------|------------------------------------------|
| **Semester**     | 8th Sem                                  |
| **Department**   | Artificial Intelligence and Data Science |
| **Submitted to** | Prof. Praveen Patel                     |


## Assignment Brief

> Create a small web app and apply the following:
> 1. Dockerize it
> 2. Push code to GitHub
> 3. Configure GitHub Actions:
>    - On push → Run tests
>    - Build Docker image
>    - Deploy locally

---

## ✨ Features

* 🔐 Generate strong, secure passwords
* 🧠 Memorable password mode (human-friendly passwords)
* 📏 Adjustable password length (6–64)
* 🔤 Character customization:

  * Uppercase
  * Lowercase
  * Numbers
  * Symbols
* 🚫 Avoid confusing characters (O, 0, l, 1)
* 📊 Password strength indicator (visual meter)
* 📋 One-click copy with notification
* 📜 Password history (last 10 generated)
* ⚡ Generate multiple passwords instantly
* 🌗 Dark / Light mode with persistence
* 📱 Fully responsive (mobile + desktop)

## 🛠️ Tech Stack

* HTML5
* CSS3 (Glassmorphism UI)
* Vanilla JavaScript
* Docker
* GitHub Actions (CI/CD)

## 📂 Project Structure

```
Secure-Pass/
│
├── index.html
├── Dockerfile
├── README.md
├── .gitignore
├── LICENSE
└── .github/
    └── workflows/
        └── ci.yml
```

## 🐳 Docker Setup

### Build Image

```
docker build -t secure-pass .
```

### Run Container

```
docker run -p 8080:80 secure-pass
```

### Access Application

```
http://localhost:8080
```

## ⚙️ CI/CD Pipeline

This project uses GitHub Actions to automate:

* Code checkout
* Build Docker image
* Run container (basic validation)

Workflow file:

```
.github/workflows/ci.yml
```

## Push to GitHub

```bash
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/<your-username>/Secure-Pass.git
git push -u origin main
```

## 🚀 Deployment

The application can be deployed using:

* Docker (local or cloud)
* Render (recommended)
* AWS / Azure / GCP

## 🎯 Learning Outcomes

* Understanding Docker containerization
* Implementing CI/CD pipelines
* Designing modern UI/UX
* Building real-world mini web applications

## 📜 License

This project is licensed under the MIT License.
