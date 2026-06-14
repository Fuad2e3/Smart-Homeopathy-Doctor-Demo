<div align="center">

# 🩺 Smart Homeopathy Doctor
### The Ultimate AI-Powered Homeopathic Healthcare Ecosystem

[![Platform](https://img.shields.io/badge/Platform-Flutter-blue?style=for-the-badge&logo=flutter)](https://flutter.dev/)
[![Language](https://img.shields.io/badge/Language-Dart-0175C2?style=for-the-badge&logo=dart)](https://dart.dev/)
[![Backend](https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=nodedotjs)](https://nodejs.org/)
[![API](https://img.shields.io/badge/API-Express.js-000000?style=for-the-badge&logo=express)](https://expressjs.com/)
[![Database](https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge&logo=mysql)](https://www.mysql.com/)
[![AI](https://img.shields.io/badge/AI-Gemini-blueviolet?style=for-the-badge&logo=google-gemini)](https://deepmind.google/technologies/gemini/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**Empowering patients with cutting-edge AI diagnosis, expert consultations, and a comprehensive homeopathic database.**

---

</div>

## 🌟 Overview

**Smart Homeopathy Doctor** is a revolutionary mobile application designed to bridge the gap between traditional homeopathy and modern AI technology. Developed by **Team Softece**, this platform provides a seamless experience for users seeking natural healing through intelligent symptom analysis and professional guidance.

## 🚀 Key Features

-   🤖 **AI-Powered Symptom Analysis**: Leveraging Google's Gemini AI to analyze symptoms and suggest potential homeopathic remedies.
-   👨‍⚕️ **Doctor Consultations**: Connect with certified homeopathic practitioners for personalized treatment plans.
-   📚 **Remedy Database**: A vast library of homeopathic medicines with detailed information on usage and benefits.
-   📅 **Appointment Scheduling**: Easy booking system for virtual or in-person consultations.
-   🛒 **Medicine Marketplace**: A dedicated space to browse and purchase genuine homeopathic products.
-   📱 **Personal Health Tracker**: Maintain a history of your symptoms, diagnoses, and treatments.

## 🛠️ Tech Stack

-   **Frontend**: Flutter (Dart)
-   **Backend**: Node.js, Express.js
-   **Database**: MySQL
-   **REST API**: Custom-built for seamless client-server communication
-   **AI Engine**: Google Gemini API
-   **Architecture**: MVC (Model-View-Controller) / MVVM

## 📁 Project Structure

```text
Smart-Homeopathy-Doctor/
├── client/                      # Flutter Application
│   ├── lib/                     # Dart source code
│   │   ├── models/
│   │   ├── screens/
│   │   ├── services/            # API communication
│   │   └── widgets/
│   ├── assets/                  # Images, fonts, and local data
│   └── pubspec.yaml
├── server/                      # Node.js Express Backend
│   ├── config/                  # Database configuration
│   ├── controllers/             # Business logic
│   ├── models/                  # MySQL models
│   ├── routes/                  # API endpoints
│   ├── index.js                 # Entry point
│   └── package.json
└── LICENSE                      # MIT License
```

## ⚙️ Installation

### Backend Setup (Node.js)
1.  **Navigate to server directory**:
    ```bash
    cd server
    ```
2.  **Install dependencies**:
    ```bash
    npm install
    ```
3.  **Configure Environment Variables**:
    - Create a `.env` file and add your MySQL and Gemini API credentials.
4.  **Run the server**:
    ```bash
    npm start
    ```

### Frontend Setup (Flutter)
1.  **Navigate to client directory**:
    ```bash
    cd client
    ```
2.  **Install packages**:
    ```bash
    flutter pub get
    ```
3.  **Run the app**:
    ```bash
    flutter run
    ```

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="center">
  Developed with ❤️ by <b>Team Softece</b><br>
  <i>Smart Homeopathy Doctor</i>
</p>
