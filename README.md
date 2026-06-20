<div align="center">

<img src="toolkit_hero.svg" alt="Medicine Reminder Application " width="600"/>

# 🖼️ Medicine Reminder Application

**A modern desktop app to Edit, Transform and Enhance images — built with Python & Tkinter**

![Python](https://img.shields.io/badge/Python-3.7+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-6366f1?style=for-the-badge)
![Pillow](https://img.shields.io/badge/Pillow-PIL-ff6b6b?style=for-the-badge)
![NumPy](https://img.shields.io/badge/NumPy-Matrix-013243?style=for-the-badge&logo=numpy&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-22d3ee?style=for-the-badge)

[Features](#-features) · [Screenshots](#-screenshots) · [Demo](#-demo-video) · [Installation](#-installation) · [Usage](#-how-to-use) · [Tech Stack](#-tech-stack)

</div>

---

## 📌 About The Project

A desktop application built using Tkinter that helps users manage and track their medicine schedules with real-time reminders.
---

## ✨ Features

### 🎨 Filter & Effects
| Feature | Description |
|---|---|
| **Authenticstion** | User authentication (Login & Signup using MySQL) |
| **Add Medicine** | Add medicines with scheduled reminder times |
| **Show Medicine** | View medicines in a dynamic table |
| **Delete Medicine** | Delete medicines with a double-click |
| **Alert** | Real-time reminder alerts (checks every minute) |
| **Greaeing** | Personalized greeting for logged-in users |
---

## 📸 Screenshots

> **Login Screen**

![Home Screen](screenshots/home.png)

> ** Create New User Acount **

![Editor Filters](screenshots/editor_filters.png)

> ** Authentication Window **

![Editor Transforms](screenshots/editor_transform.png)

> **Add Medicine / Reminder Alert**

![Before After](screenshots/before_after.png)

---

## 🎬 Demo Video

> Click the thumbnail below to watch the full demo on YouTube

[![Watch Demo](https://img.shields.io/badge/▶_Watch_Demo-YouTube-FF0000?style=for-the-badge&logo=youtube)](https://youtube.com/your-video-link)

<!-- Replace the link above with your actual YouTube video URL -->
<!-- To embed a video thumbnail directly:
[![Demo Video](https://img.youtube.com/vi/YOUR_VIDEO_ID/maxresdefault.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)
-->

---

## 🛠️ Tech Stack

| Technology | Role |
|---|---|
| **Python 3.7+** | Core language |
| **Tkinter** | GUI framework (built into Python) |
| **MySQL (Database)** | authencation user , save data, retrive data |
| **Datetime Module** |for calculate current time |

### Why MySQL for saving data?
MySQL can support (MySQL stores medicine and user data permanently, provides fast access, and allows easy management of records.)
---

## 📁 Project Structure

```
Medicine Reminder Project
│
├── main.py
├── database.py
├── reminder.py
├── gui.py
├── mysql_database
│   ├── users
│   └── medicines
│
├── assets
│   ├── icons
│   └── images
│
├── requirements.txt
└── README.md
---

## Installation
1. Clone the Repository
git clone https://github.com/yourusername/Medicine-Reminder-System.git
cd Medicine-Reminder-System
2. Create Virtual Environment
Windows:
python -m venv venv
venv\Scripts\activate
Linux/Mac:
python3 -m venv venv
source venv/bin/activate
3. Install Dependencies
pip install -r requirements.txt
Or install manually:
pip install mysql-connector-python
pip install customtkinter
pip install plyer
MySQL Setup
Login to MySQL:
mysql -u root -p
Create Database:
CREATE DATABASE medicine_reminder;
USE medicine_reminder;
Create Table:
CREATE TABLE medicines (
    id INT AUTO_INCREMENT PRIMARY KEY,
    medicine_name VARCHAR(100),
    dosage VARCHAR(50),
    reminder_time TIME,
    start_date DATE,
    end_date DATE
);
Configure Database
Open database.py and update:
host="localhost"
user="root"
password="your_password"
database="medicine_reminder"
Run the Project
python main.py
Technologies Used
Python
MySQL
CustomTkinter
MySQL Connector
Plyer Notifications
Future Improvements
Email reminders
SMS notifications
Cloud database integration
User authentication
Mobile application support
---

## 🤝 Contributing

Contributions are welcome! If you find a bug or want to add a feature:

1. Fork the repository
2. Create your branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — you are free to use, modify, and distribute it.

---

## 👨‍💻 Author

<div align="center">

**Daksh Sharma**

[![GitHub](https://img.shields.io/badge/GitHub-Eagle_Head-181717?style=for-the-badge&logo=github)](https://github.com/your-username)
[![YouTube](https://img.shields.io/badge/YouTube-Eagle_Head_YT-FF0000?style=for-the-badge&logo=youtube)](https://youtube.com/your-channel)

*Built with 💜 using Python*

© 2025 Eagle Head | Daksh Sharma

</div>
