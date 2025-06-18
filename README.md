<h1 align="center">KomunaH2M</h1>
<h3 align='center'>Software Engineer | AI, ML, DL & Computer Vision</h3>
<p align="center">
  <!-- Languages and Frameworks -->
  <img src="https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-0.110.0-009688?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-16.2-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/Angular-17-DD0031?style=for-the-badge&logo=angular&logoColor=white">
  <img src="https://img.shields.io/badge/Flutter-3.22-02569B?style=for-the-badge&logo=flutter&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-24.0.7-2496ED?style=for-the-badge&logo=docker&logoColor=white">
</p>

## 📖 Description

An intelligent, multi-role, cross-platform community management system based on FastAPI, Angular, and Flutter. **KomunaH2M** allows you to manage communities, meetings, finances, and support with support for AI integration.

## 🌐 Vision

> Digitize and empower community organization by combining technology, transparency, and citizen participation in a single platform.

## 🎯 Key Features

- ✅ Multi-community support (multi-tenant)
- 🧑‍🤝‍🧑 Custom roles per community:
  - President
  - Vice President
  - Secretary
  - Treasurer
  - Trustee
  - Member
- 🗓️ Meeting scheduling and attendance tracking
- 📝 Document creation, review, and digital signatures
- 💰 Monthly contribution tracking
- 📊 Financial reports and contribution history
- 📷 AI-powered attendance via face recognition
- 📱 Access via web (Angular) and mobile app (Flutter)

## 🛠️ Tech Stack

- **Backend**: FastAPI, PostgreSQL, SQLModel, JWT
- **Frontend Web**: Angular
- **Mobile App**: Flutter
- **Others**: Docker, Docker Compose, GitHub Actions (CI/CD)

## 📁 Project Structure

KomunaH2M/
├── backend/ # FastAPI REST API
├── frontend-web/ # Angular web admin
├── frontend-app/ # Flutter mobile app
├── docker-compose.yml
└── README.md


## ⚙️ Quick Start

### Requirements

- Python 3.10+
- Node.js 18+ with Angular CLI
- Flutter SDK
- Docker and Docker Compose

### Local Setup

```bash
# Clone the project
git clone https://github.com/henrymeza/KomunaH2M.git
cd KomunaH2M

# Backend
cd backend
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload

# Frontend Web
cd ../frontend-web
npm install
ng serve

# Flutter App
cd ../frontend-app
flutter pub get
flutter run
```

Or run everything with Docker:
```bash
docker-compose up --build
```

## 🚧 Project Status

<details open>
<summary>Architecture designed:</summary>
  
- `Backend:` Authentication and community management
- `Frontend Web:` Login and dashboards
- `Flutter App:` Member view and meeting tracking
- `AI:` Attendance recognition module
</details>

## 🤖 AI Plans

We plan to integrate:

- Face recognition for meeting attendance
- Smart document processing and digital signatures
- Automated community reports

## ⭐ Support the Project

Star ⭐ the repository and share it with community leaders who could benefit from digital tools like KomunaH2M.

## ✨ Autor

Henry Meza

<br>
<div align="center">
  <a href="https://github.com/hpmezam">
    <img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-github.png" width="3%" alt="Ultralytics GitHub">
  </a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://www.linkedin.com/in/hpmezam/">
    <img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-linkedin.png" width="3%" alt="Ultralytics LinkedIn">
  </a>
</div>

