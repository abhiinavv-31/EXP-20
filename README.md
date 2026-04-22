# 🚀 Experiment-20: CI/CD Pipeline Implementation

## 📌 Objective
To implement a CI/CD pipeline for application deployment using GitHub Actions and Docker.

---

## 🛠 Tools & Technologies Used
- Python (Flask)
- Git & GitHub
- GitHub Actions (CI)
- Docker (CD)

---

## ⚙️ Project Description

This project demonstrates a complete CI/CD pipeline:

- A simple Flask backend application
- Unit testing using Python `unittest`
- Continuous Integration using GitHub Actions
- Containerization using Docker

---

## 🧩 Steps Performed

### 🔹 1. Backend Development
- Created a Flask application (`app.py`)
- Endpoint `/` returns:
---

### 🔹 2. Testing
- Created test file (`test_app.py`)
- Used `unittest` to verify API response
- Ensured status code is `200 OK`

---

### 🔹 3. Version Control
- Initialized Git repository
- Pushed project to GitHub

---

### 🔹 4. CI Pipeline (GitHub Actions)
- Created workflow file:
- Automated:
- Code checkout
- Dependency installation
- Test execution

---

### 🔹 5. Docker Integration (CD)
- Created `Dockerfile`
- Built Docker image
- Ran container locally

---

## 🐳 Docker Commands Used

```bash
docker build -t exp20-app .
docker run -d -p 5001:5000 exp20-app
