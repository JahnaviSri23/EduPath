# 🎓 EduGuide Pro  
Smart Digital Career & College Guidance Platform  

---

## 📌 Project Overview

EduGuide Pro is a full-stack web application designed to help students after Class 10 and 12 make informed decisions about:

- Choosing the right stream (Arts, Science, Commerce)
- Selecting suitable degree programs
- Understanding career opportunities
- Identifying nearby government colleges
- Making data-driven academic decisions

This platform aims to increase enrollment in government degree colleges and reduce student dropouts.

---

## 🧠 Problem Statement

Many students and parents lack clarity about:

- Which subject stream to choose
- What career options are available after graduation
- Whether graduation is worth pursuing
- Which government colleges are available nearby

Due to this lack of awareness:
- Students make poor academic decisions
- Dropout rates increase
- Enrollment in government colleges decreases

---

## 🎯 Proposed Solution

EduGuide Pro provides:

✔ Personalized stream recommendation  
✔ Marksheet upload and percentage analysis  
✔ Degree and career mapping  
✔ User dashboard  
✔ Secure login system  
✔ Modern responsive UI  

---

## 🏗 System Architecture

Frontend (HTML + CSS + Bootstrap)
        ↓
Backend (Python Flask)
        ↓
Database (MySQL)

---

## ⚙️ Technology Stack

### Frontend
- HTML5
- CSS3
- Bootstrap 5

### Backend
- Python
- Flask Framework

### Database
- MySQL

### Tools
- Git & GitHub
- VS Code

---

## 📂 Project Structure

EduGuide/
│
├── app.py                → Main backend file
├── schema.sql            → Database structure
│
├── templates/            → HTML pages
│   ├── base.html
│   ├── login.html
│   ├── register.html
│   ├── upload.html
│   └── dashboard.html
│
├── static/
│   └── css/
│       └── style.css
│
├── uploads/              → Uploaded certificates folder
│
└── README.md

---

## 🗄 Database Design

### 1️⃣ Users Table

Stores registered users.

Fields:
- user_id (Primary Key)
- name
- email
- password

---

### 2️⃣ Certificates Table

Stores uploaded marksheets and recommendations.

Fields:
- certificate_id (Primary Key)
- user_id (Foreign Key)
- file_path
- percentage
- suggested_stream

---

## 🔑 Core Features

### 1️⃣ User Registration
Students can create a new account.

### 2️⃣ Login System
Secure login with session handling.

### 3️⃣ Marksheet Upload
Students upload their Class 10/12 certificate (PDF/JPG).

### 4️⃣ Recommendation Engine
Based on percentage:

- > 85% → Science + Competitive Exams
- 70–85% → Science / Commerce
- 60–70% → Commerce / Professional Courses
- < 60% → Arts / Skill-Based Programs

### 5️⃣ Personalized Dashboard
Displays:
- Uploaded percentage
- Suggested stream
- Career direction

---

## 🔄 Working Flow

1. User registers
2. User logs in
3. User uploads marksheet
4. System analyzes percentage
5. Stream recommendation generated
6. Dashboard displays result

---

## 🚀 Installation Guide

### Step 1: Clone Repository

git clone <repository-link>

---

### Step 2: Install Required Packages

pip install flask mysql-connector-python werkzeug

---

### Step 3: Setup MySQL Database

Open MySQL and run:

CREATE DATABASE eduguide;
USE eduguide;

Then execute schema.sql file.

---

### Step 4: Run Application

python app.py

Open browser:
http://127.0.0.1:5000

---

## 🔐 Security Features

- Secure file upload handling
- Session-based login
- Restricted file types (PDF, JPG, PNG)

---

## 📈 Future Enhancements

- OCR-based automatic marks reading
- AI-based recommendation engine
- Scholarship eligibility checker
- College search by district
- Admin dashboard
- Mobile application

---

## 👥 Team Members (4 Members)

Member 1 – Frontend Developer  
Member 2 – Backend Developer  
Member 3 – Database & Logic Developer  
Member 4 – Documentation & Feature Enhancement  

---

## 🎯 Expected Impact

- Increase enrollment in government colleges
- Reduce dropout rates
- Improve career awareness
- Provide data-driven guidance

---

## 📌 Conclusion

EduGuide Pro serves as a Smart Education platform that bridges the awareness gap between students and higher education opportunities, helping them make informed and confident academic decisions.

---

## 👩‍💻 Developed By

Team Name : PYSQUARD 
College Name : SRM UNIVERSITY
Year  : 2024-2028
