# 🧾 Payroll Management System

A robust full-stack web application for managing employee payroll, attendance, and leave tracking using Python, Flask, and SQLite.

## 🔧 Tech Stack
- **Backend:** Python, Flask
- **Database:** SQLite
- **Frontend:** HTML, CSS, Jinja Templates
- **Design Patterns Used:** Strategy, Observer, State, Singleton

## 🚀 Features
- Employee CRUD operations (Add, Update, Delete, View)
- Payroll computation with Strategy pattern
- Real-time salary dashboard and attendance tracking
- Leave request workflow with State pattern
- Notifications using Observer pattern
- Secure login and role-based access

## 📁 Folder Structure
- `/templates` – HTML files (Jinja templating)
- `/static` – CSS and JS
- `app.py` – Main application logic
- `payroll_system.db` – SQLite database

## 🧠 Design Patterns
- **Strategy:** Switchable payroll calculation methods
- **Observer:** Notifications for attendance events
- **State:** Manage leave request statuses
- **Singleton:** Single DB connection instance

## 📸 Screenshots
_Add screenshots of dashboard, payroll page, attendance form here._

## 🛠️ How to Run
```bash
git clone https://github.com/Saruleka/Payroll-system.git
cd Payroll-system
pip install -r requirements.txt
python app.py
