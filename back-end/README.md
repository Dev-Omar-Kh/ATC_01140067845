# 🖥️ Backend - Event Booking Platform

This is the Node.js + Express backend for the event booking system.

## ⚙️ Setup

```bash
cd backend
npm install
npm run dev
```

## 🔐 Environment Variables

Create a `.env` file with:

```
PORT=5000
MONGO_URI="mongodb+srv://omermo3434:5RegwERKIxfafo1N@cluster0.j6cs1.mongodb.net/Eventra"
JWT_SECRET="someverysecretkey"
```

## 📌 Features

- User & Admin authentication (JWT)
- Middleware for role-based access
- CRUD API for events
- Booking API
- Upload to Cloudinary
