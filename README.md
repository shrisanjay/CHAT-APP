# ✨ Full Stack Real-Time Chat Application ✨

## 🚀 Overview

This project is a full-featured real-time chat application built using the **MERN** stack (MongoDB, Express, React, Node.js) along with **Socket.io** for real-time communication. It comes with a sleek UI styled using **Tailwind CSS** and **Daisy UI**.

## 🔥 Features

* 🔐 **Authentication & Authorization** using JWT for secure access
* 💬 **Real-time messaging** with **Socket.io**
* 🟢 **Online user presence/status** indicator
* 📦 **Global state management** handled using Zustand
* 🛠️ **Robust error handling** on both client and server sides

---

## ⚙️ Environment Setup

Before running the app, create a `.env` file in the root directory and configure it as follows:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development
```

---

## 🛠️ Build the App

```bash
npm run build
```

## ▶️ Start the App

```bash
npm start
```
