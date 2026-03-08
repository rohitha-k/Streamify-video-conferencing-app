# 🎥 Streamify – Video Conferencing Application

Streamify is a full-stack video conferencing and chat application that allows users to communicate and collaborate in real time.
The application supports authentication, friend management, chat, and video calling using modern web technologies.

---

# 🚀 Live Demo

The application is deployed on **Render**.

🔗 Live Application:
https://streamify-video-conferencing-app-1.onrender.com



---

# 🚀 Features

* User authentication (Signup / Login)
* Real-time video calling
* Real-time chat system
* Friend request and management
* Secure authentication using JWT
* Modern responsive UI
* Theme customization

---

# 🛠️ Tech Stack

## Frontend

* React
* Vite
* Tailwind CSS
* Axios

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

## External Services

* Stream API (Video & Chat)

---

# 📂 Project Structure

```
Streamify-video-conferencing-app
│
├── BACKEND
│   ├── src
│   │   ├── controllers
│   │   ├── routes
│   │   ├── models
│   │   ├── middleware
│   │   ├── lib
│   │   └── server.js
│   │
│   └── package.json
│
├── FRONTEND
│   ├── src
│   │   ├── Components
│   │   ├── pages
│   │   ├── hooks
│   │   ├── lib
│   │   └── main.jsx
│   │
│   └── package.json
│
└── package.json
```

---

# ⚙️ Installation

## 1️⃣ Clone the repository

```
git clone https://github.com/rohitha-k/Streamify-video-conferencing-app.git
cd Streamify-video-conferencing-app
```

---

## 2️⃣ Install Dependencies

### Backend

```
cd BACKEND
npm install
```

### Frontend

```
cd ../FRONTEND
npm install
```

---

# 🔑 Environment Variables

## Backend `.env`

Create a `.env` file inside the **BACKEND** folder.

Example:

```
PORT=5001
MONGO_URI=your_mongodb_connection_string
STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret
JWT_SECRET=your_jwt_secret

NODE_ENV=production
```

---

## Frontend `.env`

Create a `.env` file inside the **FRONTEND** folder.

Example:

```
VITE_STREAM_API_KEY=your_stream_api_key
```

⚠️ Note:
For Vite projects, environment variables must start with **VITE_**.

---

# ▶️ Running the Application Locally

### Start Backend

```
cd BACKEND
npm run dev
```

### Start Frontend

```
cd FRONTEND
npm run dev
```

Frontend runs at:

```
http://localhost:5173
```

---

# 🌐 Deployment

The application is deployed using:

* **Render** → Full stack deployment
* **MongoDB Atlas** → Database
* **Stream API** → Video and chat functionality

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Rohitha**

GitHub:
https://github.com/rohitha-k
