
```markdown
# ⚙️ FixItHub – Backend (Flask API)

🔗 Frontend: https://fix-it-hub-rho.vercel.app/  

---

## 📌 Overview

This repository contains the **Flask backend API** for FixItHub, a full-stack community issue reporting platform.

The backend manages:
- User authentication
- Issue reporting & tracking
- Comments and voting
- Admin operations

---

## ⚙️ Tech Stack

- Python (Flask)
- MongoDB Atlas (Database)
- JWT Authentication
- Cloudinary (Image storage)

---

## 🔑 Core Features

- 🔐 JWT-based authentication
- 📝 Issue CRUD operations
- 💬 Comment system
- 👍 Voting system
- 🏛️ Admin dashboard APIs
- 📊 Data management with MongoDB

---

## 🗄️ Database Design

Collections:
- users
- issues
- comments
- admin

Indexes used for:
- email (unique)
- reported date (performance)

---

## 🔐 Security & Validation

- Server-side validation for all inputs
- JWT token verification
- Protected API endpoints

---

## 🧪 Testing

- Python unittest / pytest
- API testing for:
  - authentication
  - issue management
  - data validation

---

## 🔄 CI/CD Pipeline

- GitHub Actions workflow:
  - Install dependencies
  - Run tests
  - Build Docker image
  - Push to DockerHub

---

## 🐳 Docker

- Containerized backend service
- Ensures consistent deployment environment

---

## 🚀 Deployment

- Hosted on **Render**
- Auto-deploy on push to main branch

---

## ▶️ Run Locally

```bash
git clone https://github.com/bestorbust/fixithub-backend.git
cd fixithub-backend
pip install -r requirements.txt
python main.py
