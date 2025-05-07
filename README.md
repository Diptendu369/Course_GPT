# 📚 Full-Stack Course Management App
# Course_GPT

A modern full-stack course management platform built with **Next.js**, **Node.js**, **Express**, **MongoDB**, and **Firebase**, styled using **Tailwind CSS** and **ShadCN UI** components.

## 🚀 Features

- 🔐 Secure login with Firebase Authentication
- 🧑‍🏫 Dashboard for managing courses and lessons
- 📄 Dynamic topic generation for lessons
- 🗂️ File uploads for course attachments
- 📊 Interactive charts and UI components
- 🌙 Theme switcher (light/dark mode)
- 🔧 Responsive and modern design

---
## 🖼️ Screenshots
### 🧭 Dashboard
![Dashboard](https://github.com/Diptendu369/Course_GPT/blob/main/SS/Screenshot%202025-05-07%20223032.png)

### 🔐 Course Page
![Login Page](https://github.com/Diptendu369/Course_GPT/blob/main/SS/Screenshot%202025-05-07%20222904.png)

### 📚 Home Page
![Create Course](https://github.com/Diptendu369/Course_GPT/blob/main/SS/Screenshot%202025-05-07%20223102.png)

---


## 📁 Project Structure
```
├── client/ # Frontend (Next.js + Tailwind CSS)
└── server/ # Backend (Node.js + Express + MongoDB)

```
---

## 🛠️ Tech Stack

### Frontend
- Next.js 13+ (App Router)
- TypeScript
- Tailwind CSS
- ShadCN UI
- Firebase (Auth & Storage)

### Backend
- Node.js
- Express.js
- MongoDB (via Mongoose or native driver)
- dotenv

---

## 🧑‍💻 Local Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Diptendu369/Course_GPT.git
cd Course_GPT


```
2. Install Dependencies
Frontend
```
cd client
pnpm install
```
Backend
```
cd ../server
pnpm install
```
3. Environment Variables
Frontend → client/.env.local

```
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
# Add other Firebase-related variables
```





