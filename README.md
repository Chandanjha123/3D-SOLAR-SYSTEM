# 🌌 3D Solar System

## 🚀 About the Project
This **3D Solar System** is an interactive educational project built using **React** and **Three.js**, featuring realistic 3D planets, the Sun, and asteroids. Users can explore the solar system and view planet information by interacting with the 3D models. Authentication is integrated via **Firebase**, ensuring a personalized experience.

## ✨ Features
- **Realistic 3D Planets & Sun** – Built using **Tripo3D.ai** for a stunning visual experience.
- **Smooth Animations** – Planets orbit the Sun in a realistic manner.
- **Interactive Planet Info** – Click on a planet to view its details, including:
  - Size
  - Rotation Time
  - Revolution Time
  - Distance from the Sun
  - Interesting Facts
- **User Authentication** – Users must log in or sign up to explore the solar system.
- **User Menu** –
  - For new users: **Sign Up** & **About**
  - For logged-in users: **Logout** & **About**

## 🛠 Tech Stack
- **React.js** – Frontend framework
- **Three.js** – 3D rendering
- **Firebase** – Authentication
- **CSS & JavaScript** – Styling & scripting

## 📂 Project Structure
```
3D-Solar-System/
│── src/
│   │── components/
│   │   │── planets/
│   │   │   │── Sun.jsx
│   │   │   │── Mercury.jsx
│   │   │   │── Venus.jsx
│   │   │   │── Earth.jsx
│   │   │   │── Mars.jsx
│   │   │   │── Jupiter.jsx
│   │   │   │── Saturn.jsx
│   │   │   │── Uranus.jsx
│   │   │   │── Neptune.jsx
│   │   │   │── Asteroids.jsx
│   │   │
│   │   │── planetInfo/
│   │   │   │── MercuryInfo.jsx
│   │   │   │── VenusInfo.jsx
│   │   │   │── EarthInfo.jsx
│   │   │   │── MarsInfo.jsx
│   │   │   │── JupiterInfo.jsx
│   │   │   │── SaturnInfo.jsx
│   │   │   │── UranusInfo.jsx
│   │   │   │── NeptuneInfo.jsx
│   │
│   │── firebase.js  # Handles authentication
│   │── App.js       # Main application file
│   │── index.js     # Entry point
```

## 🏁 How to Run the Project
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/3D-Solar-System.git
cd 3D-Solar-System
```
### 2️⃣ Install Dependencies
```sh
npm install
```
### 3️⃣ Setup Firebase
- Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
- Enable **Authentication** (Email/Password)
- Copy your Firebase configuration into `firebase.js`

### 4️⃣ Run the Application
```sh
npm start
```

## 🌍 How to Use
1. **Sign Up or Log In** – Users must authenticate before exploring the solar system.
2. **Navigate the Solar System** – Click and drag to explore the 3D environment.
3. **View Planet Information** – Click on any planet to reveal details in an overlay.
4. **Use the User Menu** –
   - **New Users:** Sign up and read about the project.
   - **Logged-In Users:** Logout or view the about section.

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repo and submit pull requests.

## 📜 License
This project is licensed under the **MIT License**.

## 📬 Contact
For any inquiries, reach out via [kd.jha000@gmail.com].

