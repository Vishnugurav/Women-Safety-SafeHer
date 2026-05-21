# Women Safety & Emergency Assistance System

A full-stack Women Safety web application designed to provide emergency support, quick alerts, and real-time safety features for users during unsafe situations.

## 🚀 Features

- 🔐 User Authentication (Login/Register)
- 📍 Live Location Tracking
- 🚨 Emergency SOS Alert System
- 👥 Emergency Contact Management
- 💬 AI Safety Chatbot Assistance
- 📱 Responsive User Interface
- ☁️ Backend API Integration
- 🗄️ MongoDB Database Support

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Tools & Services
- Git & GitHub
- Render (Deployment)

---

## 📂 Project Structure

```bash
project/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── package.json
│
├── .gitignore
├── README.md
└── package.json

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Vishnugurav/Women-Safety-SafeHer.git
```

---

## 2️⃣ Move to Project Folder

```bash
cd Women-Safety-SafeHer
```

---

# 🚀 Frontend Setup

## 3️⃣ Go to Frontend Folder

```bash
cd frontend
```

---

## 4️⃣ Install Dependencies

```bash
npm install
```

---

## 5️⃣ Start Frontend

```bash
npm run dev
```

Frontend will run on:

```bash
http://localhost:5173
```

---

# 🚀 Backend Setup

Open another terminal.

## 6️⃣ Go to Backend Folder

```bash
cd backend
```

---

## 7️⃣ Install Dependencies

```bash
npm install
```

---

## 8️⃣ Start Backend

```bash
npm start
```

OR

```bash
node server.js
```

Backend will run on:

```bash
http://localhost:5000
```

---

# 🔑 Environment Variables

## Frontend `.env`

Create:

```bash
frontend/.env
```

Add:

```env
VITE_API_BASE_URL=http://localhost:5000
```

---

## Backend `.env`

Create:

```bash
backend/.env
```

Add:

```env
PORT=5000
MONGODB_URI=YOUR_MONGODB_URI
JWT_SECRET=YOUR_SECRET_KEY
```

---

# 🗄️ MongoDB Setup

1. Create MongoDB Atlas account  
2. Create cluster  
3. Copy connection string  
4. Paste inside:

```env
MONGODB_URI=
```

---

# ✅ Run Project

Frontend:

```bash
http://localhost:5173
```

Backend:

```bash
http://localhost:5000
```

---

# 🌐 Deployment

You can deploy using:

- Render
- Vercel
- Netlify

---

# 🎯 Future Improvements

- Real-time GPS tracking
- Voice command support
- Emergency SMS alerts
- AI-based threat detection
- Mobile application integration

---

# 👨‍💻 Author

Vishnu Bibhishan Gurav

B.Tech Computer Engineering Student

---

# 📄 License

This project is developed for educational and academic purposes.
