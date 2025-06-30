
<h1 align="center">📱 React Native X Clone 🚀</h1>

<p align="center">
  A full-stack, cross-platform mobile clone of <strong>X (formerly Twitter)</strong> built with React Native, Express.js, and MongoDB — featuring authentication, real-time chat, cloud image uploads, and secure backend integration.
</p>

<p align="center">
  <img src="/mobile/assets/images/screenshot-for-readme.png" alt="App Screenshot" width="400" />
</p>

---

## 🧩 Project Overview

**X Clone** is a feature-rich social media mobile application developed using React Native for the frontend and Node.js/Express with MongoDB for the backend. It replicates core functionalities of X (formerly Twitter) including posting, liking, commenting, notifications, messaging, and user authentication.

* ✅ Cross-platform support for **Android** and **iOS**
* ✅ Built entirely with **JavaScript** (no need for Swift/Kotlin)
* ✅ Fully integrated **frontend, backend, and database**
* ✅ Scalable and secure architecture with production-ready features

---

## 🚀 Key Features

* 🔐 **User Authentication** using Clerk (supports Google/Apple login)
* 🏠 **Feed/Home Screen**: Post text and images (from gallery or camera)
* ❤️ **Like and Comment System** with animated modal views
* 🔔 **Notifications Tab** to track interactions
* 📬 **Messaging Tab**: Real-time chat and long-press delete feature
* 👤 **Profile Tab** with editable user profile modal
* 🔎 **Search Tab** to explore trending content
* 🚪 **Logout** support with session handling

---

## 🛠️ Tech Stack

### 📱 Mobile App

* **React Native** with **Expo**
* **Clerk** for authentication
* **Cloudinary** for image hosting
* **React Navigation**, **Redux**, **Axios**

### 🌐 Backend

* **Node.js** + **Express.js**
* **MongoDB** via **Mongoose**
* **Arcjet** for bot detection, rate-limiting, and security
* **Cloudinary** SDK for media uploads

---

## 🔐 Environment Configuration

### Backend (`/backend`)

Create a `.env` file with the following:

```env
PORT=5001
NODE_ENV=development

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

MONGO_URI=your_mongodb_connection_uri

ARCJET_ENV=development
ARCJET_KEY=your_arcjet_api_key

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

### Mobile (`/mobile`)

Create a `.env` file with:

```env
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
EXPO_PUBLIC_API_URL=your_backend_api_url
```

---

## ⚙️ Getting Started

### 1️⃣ Run the Backend

```bash
cd backend
npm install
npm run dev
```

### 2️⃣ Run the Mobile App

```bash
cd mobile
npm install
npx expo start
```

> Make sure the mobile `.env` matches your local/backend API URLs for full functionality.

---

## 📦 Deployment Notes

* Backend can be hosted on **Render**, **Railway**, or **Vercel**
* MongoDB is hosted via **MongoDB Atlas**
* Expo allows testing on real devices using **Expo Go**

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change. Follow conventional commits and maintain code structure.
