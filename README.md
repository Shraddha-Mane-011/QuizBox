
# 🎯 QuizBox

**An interactive Quiz Application built using Java, XML & Firebase**

QuizBox is a sleek Android quiz app that allows users to sign up, attempt quizzes across categories, track scores, and improve their knowledge — all backed by Firebase for real-time data and authentication.


## ✨ Features

| Feature                            | Description                                |
| ---------------------------------- | ------------------------------------------ |
| 👤 User Authentication             | Login / Signup using Firebase Auth         |
| 📚 Quiz Categories                 | Users can choose from multiple quiz topics |
| ✅ Auto-evaluation                  | Instant scoring after quiz completion      |
| 📊 Score Display                   | Shows score after quiz completion          |
| ☁️ Firebase Sync                   | Real-time data storage & retrieval         |
| 📱 Modern Android UI               | XML layouts with smooth user experience    |

---

## 🏗️ Tech Stack

| Layer          | Technology                                 |
| -------------- | ------------------------------------------ |
| Frontend       | **XML (Android UI Layouts)**               |
| Backend Logic  | **Java (Android)**                         |
| Database       | **Firebase Realtime Database / Firestore** |
| Build System   | Gradle                                     |
| IDE            | Android Studio                             |


## 📂 Project Structure

```
QuizBox/
 ├── app/src/main/java/...   # Java Source Code
 │   ├── activities           # Login, Signup, Quiz Screen, Result Screen
 │   ├── adapters             # RecyclerView adapters (if any)
 │   ├── models               # Data models (Question, User, Score)
 │   └── firebase             # Firebase helper classes
 ├── app/src/main/res/       # XML Layouts, Drawables, Values
 │   ├── layout               # UI screens
 │   ├── drawable             # Images, shapes, backgrounds
 │   └── values               # styles, colors, strings
 └── google-services.json     # Firebase config (DO NOT share secrets)
```


## 🚀 Getting Started

### ✅ Prerequisites

* Android Studio (Latest stable version)
* Java JDK 8+
* Internet connection (Firebase access)
* Firebase Account

---

### 📥 Clone the Repository

```bash
git clone https://github.com/Shraddha-Mane-011/QuizBox.git
cd QuizBox
```

---

### 🔧 Firebase Setup

1️⃣ Go to **Firebase Console**
2️⃣ Create a new Firebase project
3️⃣ Add an **Android App** → use your app package name
4️⃣ Download the `google-services.json` file
5️⃣ Paste it inside:

```
app/
 └── google-services.json
```

6️⃣ Enable services:

| Firebase Service        | Required          |
| ----------------------- | ----------------- |
| Authentication          | ✅ Email/Password  |
| Realtime DB / Firestore | ✅                 |
| Storage (optional)      | If storing images |

7️⃣ Update Firebase rules for security


### ▶️ Run the App

1. Open project in **Android Studio**
2. Sync Gradle
3. Connect Phone or Start Emulator
4. Press **Run ▶️**


## 🧠 Future Enhancements

* 🔥 Leaderboard
* 🕒 Countdown Timer UI
* 📤 Share score feature
* 📊 Admin dashboard to upload questions
* 🌙 Dark Mode
* 💬 Explanation after every answer

---

## 🧪 Testing Checklist

| Task           | Status |
| -------------- | ------ |
| User Signup    | ✅      |
| Login / Logout | ✅      |
| Fetch Quiz     | ✅      |
| Submit Quiz    | ✅      |
| Score Display  | ✅      |

