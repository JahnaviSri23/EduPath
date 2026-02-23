# 🎓 EduGuide Pro
Smart Digital Career & College Guidance Platform

## 📌 Developed For
Higher Education Department  
Government of Jammu and Kashmir  

Category: Software  
Theme: Smart Education  

---

# 🧠 Problem Statement

Many students after Class 10 and 12 lack clarity about:

- Which stream to choose (Arts, Science, Commerce)
- Which degree programs are available in nearby government colleges
- What career opportunities each course provides
- Whether pursuing graduation is beneficial

This leads to low enrollment in government colleges, poor academic decisions, and increased dropouts.

---

# 🎯 Solution

EduGuide Pro is a full-stack web platform that:

- Provides percentage-based and interest-based stream suggestions
- Allows marksheet upload
- Recommends suitable degree programs
- Displays nearby government colleges
- Tracks admission notifications
- Provides personalized dashboard

---

# 🏗 System Architecture

Frontend (HTML + CSS + Bootstrap)
        ↓
Backend (Python Flask)
        ↓
Database (MySQL)

---

# ⚙️ Tech Stack

Frontend:
- HTML5
- CSS3
- Bootstrap 5

Backend:
- Python
- Flask

Database:
- MySQL

Other Tools:
- Git
- GitHub

---

# 🗄 Database Tables

## 1️⃣ Users
- user_id (Primary Key)
- name
- email
- password

## 2️⃣ Certificates
- certificate_id (Primary Key)
- user_id (Foreign Key)
- file_path
- percentage
- suggested_stream

---

# 🔑 Features

- User Registration & Login
- Secure Session Handling
- Marksheet Upload (PDF/JPG)
- Stream Recommendation Engine
- Stylish Dashboard UI
- Responsive Design

---

# 🚀 Installation Guide

## Step 1: Clone Repository
git clone <repository-link>

## Step 2: Install Dependencies
pip install flask mysql-connector-python werkzeug

## Step 3: Setup Database
Create database:
eduguide

Import schema.sql file.

## Step 4: Run Application
python app.py

Open browser:
http://127.0.0.1:5000

---

# 📈 Future Enhancements

- AI-based recommendation engine
- OCR automatic marks extraction
- Scholarship eligibility checker
- College search by district
- Admin panel with analytics
- Mobile application version

---

# 🎯 Expected Impact

- Increased enrollment in government colleges
- Reduced dropouts
- Data-driven academic decisions
- Better awareness among students and parents

---

# 👩‍💻 Developed By
Your Name
