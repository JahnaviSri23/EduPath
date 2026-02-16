# 🎓 EduPath — One-Stop Personalized Career & Education Advisor

## 📖 Overview

EduPath is an intelligent career guidance platform designed to help students after Class 10th and 12th make informed academic decisions.
The system works as a **digital counselor** that analyzes student interests, academic performance, and location to recommend suitable streams, degree programs, colleges, and career paths.

The project aims to reduce student confusion, prevent dropouts, and increase enrollment in government colleges.

---

## ❗ Problem

Many students, especially in rural and semi-urban areas, face major difficulties:

* Not knowing which stream to choose (Arts / Science / Commerce)
* Lack of awareness about degree programs
* No information about nearby government colleges
* No clarity about future career opportunities
* Belief that graduation has no value
* Parents unable to guide due to lack of exposure

This leads to:

* Wrong course selection
* Dropouts after 10th/12th
* Migration to private colleges
* Unemployment due to poor decisions

---

## 💡 Proposed Solution

EduPath provides a personalized decision-making platform where a student:

1. Creates a profile
2. Takes an aptitude & interest test
3. Receives stream recommendation
4. Explores degree options
5. Views career paths
6. Finds nearby government colleges
7. Gets admission and scholarship alerts

The platform acts as a **24/7 virtual career counselor**.

---

## 🧠 Core Modules

### 1️⃣ User Management

* Student registration & login
* Profile storage (marks, class, interests, district)

### 2️⃣ Aptitude Assessment Module

Short questionnaire analyzing:

* logical thinking
* subject preference
* personality traits
* learning style

### 3️⃣ Recommendation Engine (AI)

Generates:

* Stream suggestion
* Degree recommendation
* Career options

### 4️⃣ College Finder

Lists nearby government colleges based on district and available courses.

### 5️⃣ Career Path Visualizer

Graphical flow showing future opportunities after each degree.

### 6️⃣ Timeline Tracker

Shows:

* admission dates
* counseling schedules
* scholarships

### 7️⃣ Dropout Prediction (ML)

Predicts risk level based on performance and interest mismatch.

---

## ⚙️ System Workflow

Student → Quiz → AI Analysis → Stream Suggestion → Course → Career → College → Alerts

---

## 🏗️ System Architecture

Frontend (Browser UI)
↓
Flask REST API
↓
Recommendation Logic
↓
MySQL Database
↓
Response to User

---

## 🛠️ Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap
* Chart.js

### Backend

* Python
* Flask Framework
* REST APIs

### Database

* MySQL

### AI

* Rule-based recommendation system

### ML

* Logistic Regression (Dropout Risk Prediction)

### Version Control

* Git & GitHub

---

## 🗄️ Database Design

### Users Table

| Field    | Type    |
| -------- | ------- |
| id       | int     |
| name     | varchar |
| class    | varchar |
| marks    | int     |
| district | varchar |

### Quiz Responses Table

| Field   | Type |
| ------- | ---- |
| user_id | int  |
| answers | text |

### Recommendations Table

| Field   | Type    |
| ------- | ------- |
| user_id | int     |
| stream  | varchar |
| degree  | varchar |

### Colleges Table

| Field    | Type    |
| -------- | ------- |
| name     | varchar |
| district | varchar |
| courses  | text    |

---

## 🔌 APIs Developed

| Method | Endpoint        | Purpose           |
| ------ | --------------- | ----------------- |
| POST   | /register       | create user       |
| POST   | /login          | authenticate user |
| GET    | /questions      | get quiz          |
| POST   | /submit-quiz    | submit answers    |
| GET    | /recommendation | get suggestions   |
| GET    | /colleges       | nearby colleges   |
| GET    | /career         | career path       |

---

## 👨‍💻 Team Responsibilities

| Member   | Role                     |
| -------- | ------------------------ |
| Member 1 | Frontend UI              |
| Member 2 | Backend APIs             |
| Member 3 | Database & Integration   |
| Member 4 | AI Logic & Visualization |

---

## ▶️ How to Run Locally

### Clone

```
git clone https://github.com/your-username/EduPath.git
cd EduPath
```

### Create Virtual Environment

```
python -m venv venv
venv\Scripts\activate
```

### Install Dependencies

```
pip install flask flask-cors mysql-connector-python
```

### Run Backend

```
python backend/app.py
```

### Open Frontend

Open:

```
frontend/index.html
```

---

## 🎯 Expected Impact

* Increase enrollment in government colleges
* Reduce wrong career decisions
* Provide free career guidance
* Help parents understand education paths
* Improve employability awareness

---

## 📊 Future Enhancements

* Mobile app version
* Voice-based guidance
* Regional language support
* Government database integration
* Scholarship auto-apply feature

---

## 📄 License

MIT License — free to use with attribution.

---

## 🙌 Acknowledgment

Developed as an academic project to support student career awareness and educational planning.
