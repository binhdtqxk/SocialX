# 🐦 SocialX – Real-Time Social Media Platform

**SocialX** is a full-stack social media platform inspired by X (formerly Twitter), developed as a university capstone project. It supports user interaction, real-time messaging, notifications, post engagement, and administrative features.

> 🔗 Frontend: [TieuLuan_FE](https://github.com/binhdtqxk/TieuLuan_FE)  
> 🔗 Backend: [TieuLuan_BE](https://github.com/binhdtqxk/TieuLuan_BE)

---

## 🚀 Tech Stack

- **Backend**: Spring Boot · Apache Kafka · WebSocket · MySQL · JDK 22 · Docker· GMail API
- **Frontend**: ReactJS · Redux · TailwindCSS · Material UI · Map box API· Cloudinary
- **Other Tools**: Docker Compose · JWT Authentication · Vite

---

## ✅ Features

### 👤 User System
- Register / Login / Forgot Password / Change Password
- Edit profile, view other users’ profiles
- Follow / Unfollow users
- Lock / Unlock user accounts (Admin)

### 📝 Post System
- Create, view, and like posts
- Comment on posts
- Repost / Undo repost

### 💬 Real-Time Features
- Direct messaging using WebSocket
- Instant notifications (Kafka + WebSocket)
- View analytics and user statistics

---

## 📂 Project Structure

This repository includes both the frontend and backend as submodules:

SocialX/
├── frontend/ # ReactJS client (from TieuLuan_FE)
└── backend/ # Spring Boot API (from TieuLuan_BE)


> Make sure to run `git submodule update --init --recursive` after cloning this repo to pull in the submodules.

---

## ⚙️ Getting Started

### 1️⃣ Clone with Submodules

```
git clone https://github.com/binhdtqxk/SocialX.git
cd SocialX
git submodule update --init --recursive
```
2️⃣ Backend Setup
```
📁 Navigate into the backend/ directory

cd backend
Ensure Docker is installed and running.

Start Kafka & MySQL using Docker Compose: run file docker-compose.yml

Open the project in an IDE with JDK 22.

Run the Spring Boot application.

The backend will be available at:
👉 http://localhost:3000
```
3️⃣ Frontend Setup
```
📁 Open a new terminal and navigate to frontend/

cd frontend
Install dependencies:

npm install
Start the development server:

npm run dev
The frontend will run at:
👉 http://localhost:5173
```
📌 Notes
This is a student project and may not be production-ready.

Backend and frontend are separated into submodules for clarity and modularity.

The platform was built for learning purposes, with focus on real-time systems using Kafka and WebSocket.

🙋 Author
Phan Thanh Bình

Student at HCMUTE (Đại học Sư Phạm Kỹ Thuật TP.HCM)

GitHub: @binhdtqxk

