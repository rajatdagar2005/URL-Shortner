# URL Shortener

A full-stack URL shortening application built with **React, Node.js, Express, and MongoDB**. Users can create short URLs, track click counts, and manage their shortened links through a clean and responsive interface.

## 🚀 Live Demo

### Frontend

https://url-shortner-kappa-one.vercel.app

### Backend API

https://url-shortner-c1um.onrender.com

### GitHub Repository

https://github.com/rajatdagar2005/URL-Shortner

---

## 📌 Features

* Create short URLs instantly
* Redirect users to original URLs
* Track URL click counts
* User authentication using JWT
* View all created URLs
* Copy shortened URLs with one click
* Responsive UI
* Cloud deployment with Vercel and Render

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* Tailwind CSS
* React Query
* Axios

### Backend

* Node.js
* Express.js
* JWT Authentication

### Database

* MongoDB Atlas
* Mongoose

### Deployment

* Vercel (Frontend)
* Render (Backend)

---

## 📂 Project Structure

```bash
URL-Shortner/
│
├── FRONTEND/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── BACKEND/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── app.js
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/rajatdagar2005/URL-Shortner.git
cd URL-Shortner
```

---

### Backend Setup

```bash
cd BACKEND
npm install
```

Create a `.env` file:

```env
PORT=3000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
APP_URL=http://localhost:3000/
FRONTEND_URL=http://localhost:5173
```

Start Backend:

```bash
npm start
```

---

### Frontend Setup

```bash
cd FRONTEND
npm install
```

Create a `.env` file:

```env
VITE_API_URL=http://localhost:3000
```

Run Frontend:

```bash
npm run dev
```

---

## 🔗 API Endpoints

### Authentication

```http
POST /api/auth/register
POST /api/auth/login
```

### URL Operations

```http
POST /api/url/shorten
GET  /api/url/user
GET  /:shortUrl
```

---

## 🌐 Deployment

### Frontend (Vercel)

```env
VITE_API_URL=https://url-shortner-c1um.onrender.com
```

### Backend (Render)

```env
APP_URL=https://url-shortner-c1um.onrender.com/
FRONTEND_URL=https://url-shortner-kappa-one.vercel.app
```

---

## 👨‍💻 Author

**Rajat Dagar**

GitHub:
https://github.com/rajatdagar2005
---

## ⭐ Support

If you found this project useful, consider giving it a star on GitHub.
