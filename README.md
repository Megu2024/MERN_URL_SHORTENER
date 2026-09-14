# 🔗 MERN URL Shortener

A simple and responsive URL Shortener built using the **MERN stack**. It converts long URLs into short, shareable links and also generates QR codes for them.

🌐 **Live Demo:** https://frontend-xgm5.onrender.com

---

## ✨ Features

- 🔗 Shorten long URLs
- 📋 Copy shortened URLs
- 🔄 Redirect shortened URLs to the original URL
- 📱 Generate QR codes for shortened URLs
- ⬇️ Download QR codes
- 📊 Track the number of clicks on shortened URLs
- 📱 Responsive and clean user interface

---

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- Tailwind CSS
- DaisyUI
- Axios
- React QR Code
- QRCode

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- NanoID
- CORS
- Dotenv

### Deployment
- Render
- MongoDB Atlas

---

## 📁 Project Structure

```text
MERN-URL-SHORTENER/
│
├── backend/
│   ├── models/
│   │   └── Url.js
│   ├── routes/
│   │   └── url.js
│   ├── .env
│   ├── package.json
│   └── server.js
│
└── frontend/
    ├── public/
    ├── src/
    │   ├── App.jsx
    │   ├── index.css
    │   └── main.jsx
    ├── .env
    ├── package.json
    └── vite.config.js
