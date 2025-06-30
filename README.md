# 🟢 Kalam Progress Tracker

A simple, scalable MERN-stack web application built during the **JPMC Code for Good Hackathon**, designed for **Kalam Foundation** to digitally track the **pre-test/post-test skill development** of women and students, especially 10th-grade dropouts and rural learners.

---

## 📚 Table of Contents

1. [Project Objective](#project-objective)  
2. [Folder Structure](#folder-structure)  
3. [Tech Stack](#tech-stack)  
4. [Features](#features)  
   - [Admin Dashboard](#admin-dashboard)  
   - [Volunteer Dashboard](#volunteer-dashboard)  
   - [Tutor Dashboard (Optional)](#tutor-dashboard-optional)  
5. [SDG Goals Addressed](#sdg-goals-addressed)  
6. [Running the Project Locally](#running-the-project-locally)  
7. [Future Scope](#future-scope)  
8. [Contributors](#contributors)  
9. [License](#license)

---

## 📌 Project Objective

> To help Kalam Foundation digitize the progress tracking of beneficiaries undergoing offline training (e.g., Stitching, Nursing, Mobile Repair, Bangle Making) through a volunteer-driven, admin-monitored platform.

---

## 📁 Folder Structure

```
Kalam_Progress_Tracker/
├── client/                        # Frontend - React (Vite)
│   ├── public/                    # Static assets
│   │   └── vite.svg
│   ├── src/
│   │   ├── assets/                # Images, logos, etc.
│   │   ├── components/            # Reusable UI components
│   │   ├── pages/                 # Dashboard, Login, Home etc.
│   │   ├── routes/                # Route definitions
│   │   ├── context/               # Auth / global state
│   │   ├── services/              # API calls (axios)
│   │   ├── App.jsx
│   │   ├── index.css
│   │   └── main.jsx
│   ├── index.html
│   ├── vite.config.js
│   ├── package.json
│   ├── package-lock.json
│   └── .gitignore

├── server/                        # Backend - Node.js + Express
│   ├── config/                    # DB connection, environment setup
│   │   └── db.js
│   ├── controllers/              # Logic for routes
│   │   └── beneficiaryController.js
│   ├── models/                   # Mongoose schemas
│   │   ├── User.js
│   │   ├── Beneficiary.js
│   │   └── TestScores.js
│   ├── routes/                   # Express routes
│   │   ├── authRoutes.js
│   │   ├── beneficiaryRoutes.js
│   │   └── adminRoutes.js
│   ├── middleware/              # JWT auth, error handling
│   │   └── authMiddleware.js
│   ├── index.js                  # Entry point
│   ├── package.json
│   ├── package-lock.json
│   └── .gitignore

├── README.md                     # Project documentation
├── .gitignore                    # Root gitignore (if needed)
└── LICENSE                       # Open-source license (MIT recommended)
```
---

## 🧑‍💻 Tech Stack

- **Frontend:** React.js + Vite  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (MongoDB Atlas)  
- **Authentication:** JWT or Session-based  
- **Styling:** Tailwind CSS / CSS Modules  
- **Charts:** Chart.js (for admin dashboard visualization)

---

## 🚀 Features

### 🟣 Admin Dashboard
- View pre/post test results  
- Track beneficiary certifications  
- Filter data by skill/year  
- Manage volunteers & generate reports  

### 🟢 Volunteer Dashboard
- Add student/woman beneficiaries  
- Enter pre/post scores  
- Assign offline tutors  
- Submit success stories  

### 🔵 Tutor Dashboard (Optional)
- View-only access (tutors are offline)  
- Assigned students display  
- Mark status as complete (optional)

---

## 🌍 SDG Goals Addressed

- 🎓 **SDG 4**: Quality Education  
- 💼 **SDG 8**: Decent Work and Economic Growth  
- 👩‍🎓 **SDG 5**: Gender Equality  

---

## ⚙️ Running the Project Locally

### 1. Clone the Repository
```bash
git clone https://github.com/Krishna6475/Kalam_Progress_Tracker.git
cd Kalam_Progress_Tracker
```
---

## 📦 Install Dependencies
### 🔹 Client
```bash
cd client
npm install
npm run dev
```

### 🔹 Server
```bash
cd server
npm install
npm start
```

---

## 🔮 Future Scope

- Machine Learning to predict performance and dropout risks  
- PDF/CSV export for audit-ready reports  
- SMS/WhatsApp notification integration  
- Offline-first data entry system for field work  
- Gamification of skill progress for students  

---

## 🤝 Contributors

- Team Seven Senses – JPMC Code for Good Hackathon 2025  
- Special thanks to **Kalam Foundation** for the impactful problem statement.

---

## 📃 License

This project is licensed under the **MIT License**.
