# 💬 Chatify

A real-time chat application built with **React, Node.js, Express, MongoDB, and Socket.io**, featuring secure JWT authentication, real-time messaging, online/offline presence, notifications, image sharing, and API rate limiting.

## 🚀 Features

* 🔐 **Custom JWT Authentication** — Secure signup/login without third-party authentication services
* ⚡ **Real-Time Messaging** — Instant messaging powered by Socket.io
* 🟢 **Online/Offline Presence** — See when users are online or offline
* ⌨️ **Typing Indicators** — Real-time typing status between users
* 🔔 **Notification & Typing Sounds** — Sound alerts with user-controlled toggle
* 📨 **Welcome Emails** — Automated welcome emails using Resend
* 🖼️ **Image Uploads** — Upload and share images using Cloudinary
* 🧰 **REST API** — Backend APIs built with Node.js and Express
* 🗂️ **MongoDB** — Persistent storage for users, messages, and application data
* 🚦 **API Rate Limiting** — Protection against excessive requests using Arcjet
* 🎨 **Modern UI** — React + Tailwind CSS + DaisyUI
* 🧠 **State Management** — Zustand for lightweight and centralized client-side state management

## 🛠️ Tech Stack

### Frontend

* React
* Tailwind CSS
* DaisyUI
* Zustand
* Socket.io Client

### Backend

* Node.js
* Express.js
* Socket.io
* JWT
* MongoDB
* Mongoose

### Third-Party Services

* **Resend** — Welcome emails
* **Cloudinary** — Image storage and delivery
* **Arcjet** — API rate limiting and security

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/chatify.git
cd chatify
```

### 2. Install Dependencies

Install backend dependencies:

```bash
cd backend
npm install
```

Install frontend dependencies:

```bash
cd ../frontend
npm install
```

### 3. Configure Environment Variables

Create a `.env` file inside the backend directory.

```env
PORT=3000
MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

RESEND_API_KEY=your_resend_api_key

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

ARCJET_KEY=your_arcjet_key
ARCJET_ENV=development
```

> Never commit your `.env` file or expose API keys publicly.

### 4. Start the Backend

```bash
cd backend
npm run dev
```

### 5. Start the Frontend

Open another terminal:

```bash
cd frontend
npm run dev
```

The application should now be available at the local frontend URL shown by Vite.
