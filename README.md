## 📌 Overview
This project showcases a **Continuous Integration (CI) pipeline** for a Node.js application using **Jenkins**.  
The pipeline automatically runs on every code push to GitHub and ensures the application builds correctly and passes all unit tests.

Jenkins is executed inside a **Docker container on Windows**, simulating a real-world CI environment used in production systems.

---

## 🔧 Tech Stack
- Jenkins (Dockerized)
- Node.js
- GitHub
- Jenkinsfile (Pipeline as Code)

---

## 📂 Project Structure
nodejs-ci-jenkins/

│── app.js

│── package.json

│── test/

│ └── app.test.js

│── Jenkinsfile


---

## 🔄 CI Pipeline Flow
1. Developer pushes code to GitHub  
2. Jenkins pipeline is automatically triggered  
3. Source code is checked out  
4. Node.js dependencies are installed  
5. Unit tests are executed  
6. Build status (success/failure) is reported  

---

## 🧠 Jenkins Pipeline Stages
- **Checkout Code**
- **Install Dependencies**
- **Run Tests**

The pipeline fails immediately if any step breaks, ensuring fast feedback to developers.

---

## 💡 What This Project Demonstrates
- Continuous Integration (CI) concept
- Jenkins Pipeline using Jenkinsfile
- GitHub and Jenkins integration
- Running Jenkins in Docker on Windows
- Fail-fast testing strategy

---

## 🚀 How to Run
1. Push code to the GitHub repository  
2. Jenkins automatically triggers the pipeline  
3. View build logs and test results in Jenkins UI  

---


<img width="2560" height="3908" alt="image" src="https://github.com/user-attachments/assets/73e37606-27b5-44b9-a464-b61199ae0ce1" />


---
