# 🧠 Nimma Arogya - AI-Enabled Patient Care Portal

An advanced, user-friendly healthcare platform that leverages AI/ML to offer smarter, faster, and more accessible medical services for patients, doctors, and hospital administrators. From symptom checking to online consultations and emergency support, this portal brings the future of digital healthcare to your fingertips.

> 💡 “One platform for complete patient care — powered by intelligence, built for impact.”

---

## 👥 Users

- 🧑‍⚕️ **Doctors**: Manage appointments, view reports, consult with patients.
- 🧑‍💼 **Hospital Admin**: Oversee departments, appointments, and system analytics.
- 🧑‍💻 **Patients**: Book appointments, consult online, track health, and store reports.

---

## 🌐 Pages & Key Features

### 🔖 Landing Page
- Eye-catching animations
- About Hospital, Doctors, and Achievements section
- Patient testimonial slider
- Smart search bar to find doctors or departments

### 🗓️ Online Appointment Booking
- Step-by-step: Select department → Doctor → Date/Time
- Patient login and appointment history
- Real-time calendar integration for doctors and patients

### 🤖 AI Symptom Checker Bot
- Smart Q&A to detect probable health conditions
- AI/ML model redirects patients to relevant specialists
- Conversational interface for intuitive use

### 📁 Electronic Health Record (EHR) Viewer
- Upload and securely store health records
- Doctors can add comments/feedback
- Patients can download and access reports anytime

### 📹 Live Teleconsultation
- Real-time video consultation with doctors
- Secure chat option for queries during or post-consultation
- Doctors can upload prescriptions; patients can download them

### 📊 Wellness Dashboard
- Daily activity logs: BMI, blood sugar, step count, etc.
- Interactive graphs for vitals over time
- Medicine reminder system with alerts

### 📰 Blog Section
- Doctor-authored articles
- Categories like mental health, diet, fitness
- Full-text search, filter by category/tags

### 🚨 Emergency Help
- SOS button to directly call an ambulance
- GPS-enabled nearby hospital locator using maps
- Live chat with a trained emergency responder

---

## 💻 Tech Stack

| Technology | Purpose |
|------------|---------|
| **React.js** / HTML / CSS | Frontend UI |
| **Node.js / Express** OR **Spring Boot / Flask** | Backend APIs |
| **MongoDB / PostgreSQL** | Database for storing users, appointments, records |
| **Socket.IO / WebRTC** | Real-time video and chat |
| **JWT / OAuth2** | Authentication & authorization |
| **Python / TensorFlow / Scikit-learn** | Symptom checker AI |
| **Google Maps API / Twilio API** | Emergency and communication services |
| **Docker** | Containerization |
| **AWS / Firebase / Azure** | Cloud deployment options |

---

## 📦 Setup Instructions

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/nimma-arogya.git
cd nimma-arogya
# Frontend
cd client
npm install

# Backend
cd ../server
npm install
# Backend
cd server
npm run dev

# Frontend (new terminal)
cd client
npm start
