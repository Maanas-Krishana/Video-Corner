# 📹 Video-Corner Private



> A modern Android video conferencing application built with **Kotlin**, **Jetpack Compose**, **WebRTC**, and **Firebase** for secure, real-time video communication.

---

# 📌 Overview



Video-Corner Private is a lightweight and secure Android video conferencing application that allows users to create or join private meeting rooms with high-quality audio and video. Built using modern Android development practices, the application leverages Jetpack Compose for UI, Firebase for backend services, and WebRTC for peer-to-peer communication.

---


# ✨ Features


- 📹 HD Video Calling
- 🎙️ Mute / Unmute Microphone
- 📷 Enable / Disable Camera
- 🔄 Switch Front & Back Camera
- 🔗 Create & Join Private Rooms
- 💬 In-Meeting Chat
- 👤 User Authentication
- 🔔 Push Notifications (Optional)
- 🌙 Material 3 Design
- ⚡ Fast & Responsive UI

---


# 🛠 Tech Stack



### Language
- Kotlin

### UI
- Jetpack Compose
- Material 3

### Architecture
- MVVM
- Repository Pattern
- StateFlow
- ViewModel
- Navigation Compose

### Backend
- Firebase Authentication
- Cloud Firestore
- Firebase Cloud Messaging (Optional)

### Real-Time Communication
- WebRTC

### Dependency Injection
- Hilt

### Async Programming
- Kotlin Coroutines
- Flow

---

# 📂 Project Structure



```
Video-Corner-Private/

├── app/
│
├── data/
│   ├── remote/
│   ├── repository/
│   └── model/
│
├── domain/
│
├── ui/
│   ├── screens/
│   ├── navigation/
│   ├── components/
│   └── theme/
│
├── webrtc/
│
├── di/
│
├── utils/
│
├── MainActivity.kt
│
└── README.md
```

---

# 🚀 Getting Started



## 1. Clone Repository

```bash
git clone https://github.com/yourusername/video-corner-private.git

cd video-corner-private
```

---

## 2. Open in Android Studio

Use the latest stable version of Android Studio (Meerkat or newer recommended).

---


## 3. Configure Firebase

- Create a Firebase project.
- Enable Authentication.
- Enable Cloud Firestore.
- Download `google-services.json`.
- Place it inside the `app/` directory.

---

## 4. Sync Gradle

Allow Android Studio to download all dependencies.

---


## 5. Run the Application

Run on:

- Android Emulator
- Physical Android Device (Android 8.0+)

---


# 📱 Application Flow



```
Splash Screen
      │
      ▼
Authentication
      │
      ▼
Home Screen
      │
      ├──────────────┐
      ▼              ▼
Create Room      Join Room
      │              │
      └──────┬───────┘
             ▼
      Video Conference
             │
             ▼
      Leave Meeting
```

---


# 📸 Screens



- Splash
- Login / Sign Up
- Home
- Create Meeting
- Join Meeting
- Video Call
- Chat
- Profile
- Settings

---


# 🔒 Permissions



```xml
CAMERA

RECORD_AUDIO

INTERNET

ACCESS_NETWORK_STATE

MODIFY_AUDIO_SETTINGS

BLUETOOTH_CONNECT

FOREGROUND_SERVICE
```

---


# 📦 Main Dependencies



- Jetpack Compose
- Material 3
- Navigation Compose
- Lifecycle Compose
- Hilt
- Firebase Authentication
- Firebase Firestore
- Firebase Cloud Messaging
- Kotlin Coroutines
- WebRTC Android SDK

---


# 🚀 Future Enhancements



- 👥 Group Video Calls
- 🖥️ Screen Sharing
- 🎥 Call Recording
- 📅 Meeting Scheduling
- 📁 File Sharing
- 😊 Emoji Reactions
- ✋ Raise Hand
- 🎙️ Noise Suppression
- 🔐 End-to-End Encryption
- 🌐 Multi-language Support

---


# 🏛 Architecture



```
Presentation Layer
│
├── Jetpack Compose
├── ViewModel
└── StateFlow
        │
        ▼
Repository Layer
        │
        ▼
Firebase + WebRTC
        │
        ▼
Peer-to-Peer Communication
```

---


# 📄 License



This project is licensed under the **MIT License**.

---

# 👨‍💻 Author



Developed using modern Android technologies including **Kotlin**, **Jetpack Compose**, **MVVM**, **Firebase**, and **WebRTC** to demonstrate a basic private video conferencing application.

⭐ If you found this project helpful, consider giving it a star!
