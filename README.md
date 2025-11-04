# 🏥 Sanjeevani Aashray – Real-Time Hospital Resource Website

🚀 **Duration:** August 2024 – December 2024  
💻 **Tech Stack:** HTML | CSS | PHP | MySQL | JavaScript | Bootstrap  

---

## 🌟 Overview

**Sanjeevani Aashray** is a real-time hospital resource management platform designed to help patients and hospitals during emergencies.  
It provides **instant updates** on the availability of hospital resources such as ICU beds, ventilators, oxygen cylinders, emergency beds, and ambulances.  

The platform ensures **secure authentication**, **fast data synchronization**, and a **user-friendly interface** for both hospitals and patients.  

---

## 🧠 Key Features

✨ **For Hospitals**
- 🏨 Add, update, and manage available hospital resources.  
- ⚙️ Real-time status updates for ICU beds, ventilators, oxygen, and ambulances.  
- 🔒 Secure login and authentication system for authorized access.  

✨ **For Patients**
- 🧾 View hospital availability and facilities in real time.  
- 📞 Contact hospitals directly or send bed booking requests instantly.  
- 🕒 Stay updated during emergencies with the latest hospital data.  

---

## 🏗️ Tech Implementation

| Layer | Description |
|-------|-------------|
| 🎨 **Frontend** | Built using **HTML**, **CSS**, and **Bootstrap** for a responsive and clean design. |
| ⚙️ **Backend** | Developed in **PHP** for handling form submissions, authentication, and data synchronization. |
| 🗄️ **Database** | **MySQL** used to store hospital and patient data securely. |
| 🔐 **Security** | Implemented validation, password hashing, and secure database interactions using prepared statements. |

---

## 🔁 Real-Time Workflow

1. 🏥 **Hospital Login:** Hospitals log in securely to update resources.  
2. 💾 **Data Storage:** Resource data is stored in the **MySQL** database.  
3. 🌐 **Patient Portal:** Patients view hospital availability in real-time.  
4. 🔄 **Instant Update:** Changes made by hospitals reflect immediately on the patient page.  

---

## 📊 Database Overview (MINOR Database)

### 🧾 Tables
- **signup** → stores user registration and login data (for hospitals/patients)  
- **hospital** → contains details like hospital name, ICU beds, ventilators, oxygen, ambulance status, etc.  

### 🗝️ Sample Fields
| Table | Field Name | Description |
|--------|-------------|-------------|
| `signup` | username | Hospital or patient name |
| `signup` | password | Encrypted user password |
| `hospital` | hospital_name | Registered hospital name |
| `hospital` | icu_beds | Number of ICU beds available |
| `hospital` | oxygen_cylinders | Oxygen availability count |
| `hospital` | ambulance | Ambulance status (Available/Not Available) |

---

## 🔐 Authentication System

- ✅ **Signup:** Hospitals and patients can create accounts via a secure registration form.  
- 🔑 **Login:** Credentials verified from the `signup` table using hashed passwords.  
- 🧱 **Session Management:** Users remain logged in securely until logout.  

---

## ⚡ Achievements

- 💡 Implemented **real-time hospital resource updates** with dynamic PHP and MySQL queries.  
- 🧰 Gained hands-on experience in **backend development**, **database management**, and **secure authentication**.  
- 🧠 Enhanced knowledge of **web security**, **performance optimization**, and **scalability** for high-demand applications.  

---

## 🧩 Future Enhancements

- 🌍 Integration with **Google Maps API** to locate nearby hospitals.  
- 📲 Real-time **SMS/Email notifications** for resource updates.  
- 📈 Analytics dashboard for hospitals to track usage and demand.  
- ☁️ Migration to **AWS Cloud** for scalable hosting.  

---






## ❤️ Acknowledgements

- 🙏 Special thanks to **UPES Dehradun** for project guidance.  
- 💬 Mentors and faculty for continuous support.  
- 💻 Open-source community for libraries and frameworks.  

---

## 📜 License

🪪 This project is developed as part of an academic assignment and is open for educational and non-commercial use.

---

