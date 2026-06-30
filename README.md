<div align="center">

# 🎓 AI-Based Online Proctoring System

### Secure AI-Powered Online Examination Platform

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Django](https://img.shields.io/badge/Django-Framework-green?logo=django)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-red?logo=opencv)
![YOLO](https://img.shields.io/badge/YOLO-Object%20Detection-orange)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?logo=postgresql)
![License](https://img.shields.io/badge/License-MIT-success)

An AI-powered online examination system that monitors students in real time using Computer Vision and Artificial Intelligence to detect suspicious activities and generate automated examination reports.

</div>

---

# 📖 Overview

Online examinations require reliable monitoring to maintain academic integrity. Traditional online invigilation relies heavily on human supervision and is difficult to scale.

This project provides an intelligent online proctoring solution that automatically monitors candidates using webcam, microphone, and browser activity. The system detects suspicious activities in real time and generates reports for administrators.

---

# ✨ Features

✅ Student Registration with Face Capture

✅ Secure Authentication

✅ AI-Based Face Detection

✅ Multiple Face Detection

✅ Eye/Gaze Tracking

✅ Object Detection (Mobile Phones & Unauthorized Objects)

✅ Browser Tab Switch Detection

✅ Live Webcam Monitoring

✅ Real-Time Alerts

✅ Automatic Cheating Report Generation

✅ Admin Dashboard

✅ Examination Management

---

# 🛠 Tech Stack

## Frontend

- HTML5
- CSS3
- Bootstrap
- JavaScript

## Backend

- Python
- Django

## Database

- PostgreSQL

## AI & Computer Vision

- OpenCV
- MediaPipe
- YOLO
- NumPy

## Real-Time Communication

- WebRTC

---

# 🧠 AI Modules

## 👤 Face Detection

Detects whether the registered candidate is present throughout the examination.

---

## 👥 Multiple Face Detection

Detects unauthorized persons appearing in front of the webcam.

---

## 👀 Gaze Tracking

Tracks eye movement to identify repeated looking away from the screen.

---

## 📱 Object Detection

Uses YOLO to detect prohibited objects such as:

- Mobile Phones
- Books
- Electronic Devices

---

## 🔄 Browser Monitoring

Detects:

- Tab Switching
- Browser Focus Loss

---

## 📊 Report Generation

Automatically records:

- Total Violations
- Warning Count
- Suspicious Activities
- Timestamps
- Final Trust Score

---

# 🏗 System Architecture

```
Student
   │
   ▼
Login & Authentication
   │
   ▼
Webcam + Microphone + Screen Capture
   │
   ▼
Preprocessing
   │
   ▼
AI Detection Module
 ├── Face Detection
 ├── Gaze Tracking
 ├── Object Detection
 └── Tab Switch Detection
   │
   ▼
Decision Engine
   │
   ▼
Alerts + Logs
   │
   ▼
Admin Dashboard
```

---

# 📂 Project Structure

```
AI-Based-Online-Proctoring-System/

│
├── accounts/
├── exams/
├── proctoring/
├── templates/
├── static/
├── media/
├── models/
├── utils/
├── requirements.txt
├── manage.py
└── README.md
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/AI-Based-Online-Proctoring-System.git
```

Move inside the project

```bash
cd AI-Based-Online-Proctoring-System
```

Create Virtual Environment

```bash
python -m venv venv
```

Activate Environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

Install Dependencies

```bash
pip install -r requirements.txt
```

Run Migrations

```bash
python manage.py migrate
```

Start Server

```bash
python manage.py runserver
```

Open

```
http://127.0.0.1:8000
```

---

# 📸 Screenshots

## 🏠 Home Page

> Add Screenshot Here

---

## 👤 Student Registration

> Add Screenshot Here

---

## 📋 Admin Dashboard

> Add Screenshot Here

---

## ⚠ Tab Switch Detection

> Add Screenshot Here

---

## 📈 Student Report

> Add Screenshot Here

---

# 🔍 Detection Workflow

1. Student Login
2. Identity Verification
3. Webcam Activation
4. Live Monitoring
5. AI Analysis
6. Suspicious Activity Detection
7. Alert Generation
8. Report Generation
9. Admin Review

---

# 📊 Cheating Detection

The system can detect:

- Face Not Detected
- Multiple Faces
- Looking Away
- Mobile Phone Usage
- Unauthorized Objects
- Browser Tab Switching
- Abnormal Activity

---

# 🔒 Security Features

- User Authentication
- Secure Login
- Role-Based Access
- Centralized Monitoring
- PostgreSQL Database
- Session Management

---

# 📈 Future Enhancements

- Voice Recognition
- Face Recognition using DeepFace
- Anti-Spoof Detection
- Live Screen Recording
- AI Trust Score
- Mobile App
- Cloud Deployment
- Email Notifications
- Multi-Camera Support

---

# 💡 Applications

- Universities
- Colleges
- Online Certifications
- Placement Tests
- Recruitment Assessments
- Government Exams

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository

2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Create a Pull Request

---

# 📜 License

This project is developed for educational and research purposes.

---



## ⭐ If you like this project, don't forget to Star the repository!
