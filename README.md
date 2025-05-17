# 🎟️ Event Booking Platform (MERN Stack)

A full-featured, multilingual event booking system built with the **MERN Stack** (MongoDB, Express, React, Node.js). Users can browse and book events, while admins manage events via a secure admin panel.

Supports:
- 🌐 English & Arabic
- 🌗 Light & Dark Modes
- 📱 Fully Responsive Design (Mobile, Tablet, Desktop)
- ☁️ Image Uploads via Cloudinary

---

## 🚀 Live Demo

🌍 Frontend: [https://eventra-one.vercel.app/]  
🌐 Backend: [https://eventra-backend-eight.vercel.app/](#)

---

## 📦 Project Structure

```
project-root/
│
├── frontend/       # React frontend
├── backend/        # Node.js + Express backend
└── README.md       # This file
```

---

## 🛠️ Tech Stack

- **Frontend:** React, React Router, Axios, i18next, TailwindCSS, Redux Toolkit
- **Backend:** Node.js, Express, MongoDB, Mongoose, JWT
- **Cloud Storage:** Cloudinary
- **Deployment:** Vercel
- **AI Tools:** ChatGPT, GitHub Copilot used during development

---

## ✨ Features

### 🧑‍💼 Authentication
- Register & Login
- Role-based access (User/Admin)
- Protected Routes & Middleware

### 📅 Events
- Event cards with type, image, date, and remaining tickets
- Filtering by type
- Pagination support
- Full event details + booking

### 🎫 Bookings
- Book one ticket per event
- View and cancel your bookings
- "Booked" label for already reserved events

### 🧾 Admin Panel
- Create / Update / Delete events
- Paginated event table
- Admin-only access

### 💡 Extra Goodies
- Multi-language support (EN/AR)
- Light/Dark mode toggle
- Fully responsive UI
- Image uploads to Cloudinary

---

## 🧑‍💻 Setup Instructions

### Prerequisites
- Node.js v18+
- MongoDB (MongoDB Atlas)
- Cloudinary account
- `.env` files for frontend and backend

---

## 📂 Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

### Frontend `.env` :
```
VITE_API_URL=https://eventra-backend-eight.vercel.app/
VITE_CLOUDINARY_CLOUD_NAME=dh6zttcrq
VITE_CLOUDINARY_UPLOAD_PRESET=events_upload
```

---

## 📂 Setup Backend

```bash
cd backend
npm install
npm run dev
```

### Backend `.env` :
```
PORT=5000
MONGO_URI="mongodb+srv://omermo3434:5RegwERKIxfafo1N@cluster0.j6cs1.mongodb.net/Eventra"
JWT_SECRET="someverysecretkey"
```

---

## 📸 Screenshots

- Proof of use of AI:
<img src="./screenshots/proof-of-use-of-ai.jpg" alt="Home Page"/>

---

## 📅 Submission Guidelines

- ✅ AI tools (ChatGPT, Copilot) were used throughout the development process
- ✅ Project submitted on GitHub
- ✅ Includes separate README files for frontend and backend
- ✅ Responsive, multilingual, and deployed

---
