# AI Resume Analyzer & Recruitment System

> An AI-powered recruitment platform that helps students build ATS-friendly resumes and assists recruiters in efficiently screening and managing candidates.

> 🚧 **Project Status:** Under Development

---

## 📖 Overview

AI Resume Analyzer & Recruitment System is a full-stack web application designed to simplify both the job application process for students and the recruitment workflow for HR professionals.

The platform consists of two dedicated portals:

- 🎓 Student Portal
- 💼 HR Portal

The system aims to improve resume quality, increase ATS compatibility, streamline recruitment, and provide an intelligent user experience.

---

# ✨ Features

## 🎓 Student Portal

- Dashboard
- Resume Builder
- Resume Upload
- ATS Resume Analysis
- Resume Enhancement Suggestions
- Job Description Match
- AI Mock Interview
- Application Tracker
- Learning Resources
- Profile Management

---

## 💼 HR Portal

- Recruitment Dashboard
- Job Management
- Candidate Management
- Resume Screening
- Interview Scheduling
- Recruitment Analytics
- Reports
- Company Profile
- Recruiter Settings

---

# 🏗️ Project Architecture

```text
Student / Recruiter
        │
        ▼
Frontend (React + Vite + Tailwind CSS + Lucide)
        │ (JWT Bearer Auth via Axios)
        ▼
Backend API (FastAPI + Python 3.11)
        ├── PyMuPDF & spaCy (PDF Section/Entity Extraction)
        ├── scikit-learn & TF-IDF Vectorizer (Resume-Job Matching ML Engine)
        └── Cloudinary (Encrypted PDF Storage)
        │
        ▼
Database (MongoDB Motor Async Driver)
```

---

# 🛠️ Tech Stack

## Frontend

- React 18
- Vite
- Tailwind CSS
- Framer Motion
- React Router DOM
- Zustand (Global State Management)
- Lucide React & React Hot Toast

## Backend & APIs

- Python 3.11+
- FastAPI (Asynchronous Web Framework)
- Uvicorn (ASGI Server)
- Motor & PyMongo (MongoDB Async ODM)
- Cloudinary Python SDK (Resume Storage)
- Python-Jose & Passlib / Bcrypt (JWT Security)

## AI, ML & NLP

- scikit-learn (Resume-Job TF-IDF Match Classifier)
- spaCy (`en_core_web_sm` NLP pipeline)
- PyMuPDF (`fitz` for structured PDF parsing)
- Vector Index & Semantic Keyword Analyzers

---

# 📂 Repository Structure

This project is maintained across multiple repositories.

| Repository | Purpose |
|------------|---------|
| AI-Resume-Frontend | Frontend Application |
| AI-Resume-Backend | Backend Services |
| AI-Resume-Docs | Documentation |

---

# 📑 Documentation

This repository contains:

- Software Requirement Specification (SRS)
- UML Diagrams
- System Design
- Architecture Diagrams
- API Documentation
- Database Design
- Project Report
- Presentation Slides
- Screenshots
- Demo Resources

---

# 🚀 Development Status

- [x] Project Planning
- [ ] UI Design
- [ ] Frontend Development
- [ ] Backend Development
- [ ] AI Integration
- [ ] Testing
- [ ] Documentation
- [ ] Deployment

---

# 🎯 Project Goals

- Improve resume quality
- Provide ATS-friendly resume analysis
- Help students prepare for placements
- Simplify recruiter workflows
- Deliver a modern recruitment platform

---

# 📌 Current Phase

The project is currently under active development.

Documentation and implementation will be updated as development progresses.

---

# 👨‍💻 Author

**Vishnu**

Computer Science Engineering Student

---

## ⭐ Future Enhancements

- AI Resume Optimization
- AI Career Recommendations
- Advanced Resume Analytics
- Interview Performance Reports
- Recruiter Collaboration Tools

---

## 📄 License

This project is developed for academic and learning purposes.