# 🌐 Frontend UI - Mind Sync Smart Glasses

This repository contains the React.js frontend for the **Mind Sync Smart Glasses** project. It allows users to interact with the system, view captured memories, and retrieve contextual information using natural language queries.

---

## 🧑‍💻 Developer Responsibility

**Interface Type:** Web Dashboard
**Technology Stack:** React.js + Tailwind CSS + Axios

---

## 🎯 Objective

To provide an intuitive and responsive UI that enables users to recall moments by querying events, viewing captured images, and reading AI-generated summaries.

---

## ⚙️ Tech Stack

* React.js (Vite based)
* Tailwind CSS
* Axios
* React Router DOM
* React Hook Form
* React Hot Toast
* Vercel (Deployment)

---

## 📁 Project Structure

```
Frontend/
├── components/        # Reusable UI elements (QueryInput, ImageGallery, ResultViewer)
├── pages/             # Routes (Home, Dashboard, Login)
├── context/           # Auth and Session context
├── services/          # Axios calls to backend
├── App.jsx            # Main app entry
├── main.jsx           # Root rendering
└── .env               # API base URL
```

---

## 🚀 Setup Instructions

```bash
git clone https://github.com/Mahesh-656/FF_Mind_Sync.git
cd Frontend
npm install
npm run dev
```

Create a `.env` file:

```env
VITE_API_BASE_URL=https://your-backend-api-url
```

---

## 🔌 Features

* 🔍 Natural language input field
* 🧠 AI-generated memory summaries
* 🖼️ View image gallery (captured by ESP32\_CAM)
* 🔁 Auto-refresh on new data
* 📱 Fully responsive (mobile + desktop)

---

## 🧪 Example Query

> **Q:** What did I do on Friday at 3PM?

> **A:** You were with Surya attending an Ethical AI seminar at 3:00 PM.

---

## 🧩 Key Components

* `QueryInput.jsx`: Accepts user questions
* `ResultViewer.jsx`: Displays memory summary
* `ImageGallery.jsx`: Shows uploaded images

---

## 🌐 Live Demo

[https://mind-sync-eight.vercel.app/](https://mind-sync-eight.vercel.app/)

---

## 👨‍🎓 Project Info

**Final Year Project**

**Title:** Mind Sync Smart Glasses

**Component:** React Frontend Dashboard

---
