# 🎓 School Activity Booking System

A web-based system built using **Django** that allows parents to browse school activities, book them for their children, manage bookings, and download an invoice in PDF format.

---

## ✨ Features

- 👤 User authentication (Register, Login, Logout)
- 📅 View upcoming school activities
- 🧒 Book an activity for a child
- ✔ Capacity enforcement (spots left)
- ❌ Cancel bookings anytime
- 📄 View invoice with total costs
- 🧾 Download invoice as PDF
- ⚠ Prevent:
  - double-booking same activity
  - booking multiple activities on the same date

---

## 🛠 Tech Stack

| Component | Technology |
|----------|------------|
| Backend | Django (Python) |
| Database | SQLite3 (default) |
| PDF Generation | ReportLab |
| Styling | Custom CSS |

---

## 🚀 Setup Instructions

### 1️⃣ Create & Activate Virtual Environment
```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
If requirements.txt is missing, install manually:
```bash
pip install -r requirements.txt
```

### 3️⃣ Apply Database Migrations
```bash
python manage.py migrate
```

### 4️⃣ Run Development Server
```bash
python manage.py runserver
```
Now open your browser and go to:
```bash
http://127.0.0.1:8000/
```

---

## 🔐 Admin Panel (Optional)

Create a Django admin superuser:
```bash
python manage.py createsuperuser
```
Admin login:
```bash
/admin/
```

---

## 👨‍💻 Author

Project developed for school activity management using Django.
