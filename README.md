# 🎓 Alumni Connect

A modern Flutter application that helps alumni stay connected through a social media-style platform. Built with **Flutter** for the frontend and **Firebase** for backend services, the app supports real-time interactions, content sharing, and user networking.

---

## 🚀 Features

### 👥 User Management
- 🔐 Alumni registration & login using **Firebase Authentication**
- 🛠️ Profile setup and updates (name, bio, profile picture)
- 👤 View and search other users

### 🧾 Social Feed
- 📸 Create image/video posts
- 📰 View posts from people you follow in a live feed
- ❤️ Like and comment (can be added as future enhancement)

### 💬 Real-Time Chat
- 💬 One-to-one chat with other users
- 📡 Instant messaging via **Firebase Realtime Database**
- 🟢 Online/offline status indicators (optional)

### 🔍 Search & Follow
- 🔍 Search alumni by name, batch, or domain
- ➕ Follow/Unfollow functionality to customize your feed

### 📂 Media Uploads
- Upload profile photos and posts using **Firebase Storage**
- Optimized media handling and image previews

---

## 🧰 Tech Stack

### Frontend
- ⚙️ **Flutter** (v3.x)
- 📱 Responsive design for Android & iOS
- 🔁 State Management: `Provider` / `Riverpod` (choose based on your code)

### Backend (Firebase)
- 🔐 Firebase Authentication
- 🗃️ Firebase Realtime Database
- ☁️ Firebase Cloud Storage
- 🔔 Firebase Cloud Messaging (optional for push notifications)

---

## 🛠️ Installation

### Prerequisites
- Flutter SDK installed
- Firebase project configured
- Android/iOS device or emulator

### Steps

```bash
git clone https://github.com/SharrolineGladia/AlumniConnect.git
cd AlumniConnect
flutter pub get
flutter run
