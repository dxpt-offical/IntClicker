# 📱 IntClicker

> A simple Android clicker app with Firebase Realtime Database, user login, real-time leaderboard, and blocking system.  
> Built with Jetpack Compose and Material3.

---

![Platform](https://img.shields.io/badge/platform-android-blue.svg)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-✅-purple)
![Firebase](https://img.shields.io/badge/Firebase-Realtime_DB-yellow)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-Active-brightgreen)

---

## 🖼️ Preview

<p align="center">
  <img src="https://via.placeholder.com/300x600.png?text=IntClicker+UI+Preview" alt="App Preview" width="250"/>
</p>

---

## ✨ Features

| Feature              | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| 🔐 Login System       | Users login with username and password stored in Firebase DB                |
| 👆 Clicker Button      | Every click is saved instantly to Firebase                                 |
| 🏆 Leaderboard        | Shows top users ranked by click count (auto updates in real time)           |
| ⛔ User Blocking      | If `block: true` in DB, displays red text: **"Blocked"** in profile screen   |
| 🎨 Material 3 Design  | Clean modern UI with dark theme enabled by default                         |

---

## 🧱 Tech Stack

| Technology     | Usage                               |
|----------------|--------------------------------------|
| Jetpack Compose| UI components and navigation         |
| Material3      | Styling and theming                  |
| Firebase DB    | Authentication and click tracking    |
| Kotlin         | Language                             |
| GitHub Actions | (optional) CI/CD                     |

---

## 🔧 Firebase Database Structure

```json
{
  "users": {
    "user1": {
      "password": "1234",
      "clicks": 27,
      "block": false
    },
    "user2": {
      "password": "qwerty",
      "clicks": 0,
      "block": true
    }
  }
}
