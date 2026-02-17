# Task 1 

A Node.js project containerized with Docker. This repository demonstrates building and running a simple Node.js application in a Docker environment.

---

## 📝 Table of Contents

- [Project Overview](#project-overview)  
- [Features](#features)  
- [Installation](#installation)  
- [Docker](#docker)  
- [Usage](#usage)   

---

## 🚀 Project Overview

Task_1_ThynkTech is a Node.js-based project that demonstrates containerization with Docker. It provides a consistent environment to run and test the application locally.

---

## ✨ Features

- Node.js application  
- Dockerized for consistent environments  
- Easy setup and local execution  

---

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/mahesh-diwan/Task_1_ThynkTech.git
cd Task_1_ThynkTech
```

Install dependencies:
```bash
npm install
```

## Docker

Build Docker Image:
```bash
docker build -t task1-thynktech .
```
Run Docker Container:
```bash
docker run -p 3000:3000 task1-thynktech
```
Access the app at: http://localhost:3000

## ⚡ Usage
Run Locally
```bash
npm start
```
Run with Docker:
```bash
docker build -t task1-thynktech .
docker run -p 3000:3000 task1-thynktech
```
