# Restaurant Menu Web Application 🍽️

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Django](https://img.shields.io/badge/Django-4.x-success)
![Database](https://img.shields.io/badge/Database-SQLite-lightgrey)
![Status](https://img.shields.io/badge/Status-Active-success)

A Django-based restaurant menu web application that allows users to view menu items digitally.  
The project also includes **QR code support**, enabling customers to access the menu easily by scanning a QR code.

---

## 📌 Project Overview

This project is designed to demonstrate the use of **Django** for building a simple yet practical web application.  
It follows Django’s standard project–app structure and uses SQLite as the backend database.

Use cases include:
- Digital restaurant menus
- QR-based menu access
- Django learning and portfolio projects

---

## 🚀 Features

- Web-based restaurant menu
- Django MVC (MVT) architecture
- SQLite database integration
- QR code generation for menu access
- Simple and clean UI using HTML templates
- Easy local setup

---

## 🛠️ Tech Stack

| Category | Technology |
|--------|------------|
| Language | Python |
| Framework | Django |
| Database | SQLite |
| Frontend | HTML, CSS |
| Utility | qrcode, Pillow |

---

## 📂 Project Structure

```text
Restaurant-Menu-djnago/
├── mysite/                 # Django project configuration
├── restaurant_menu/        # Django app (views, models, urls)
├── manage.py               # Django management script
├── db.sqlite3              # SQLite database
├── qr.py                   # QR code generation script
├── qr.png                  # Generated QR code image
├── requirements.txt
├── README.md
```

---

## ⚙️ Installation & Setup

git clone https://github.com/Rohit-more-2003/Restaurant-Menu-djnago.git<br>
cd Restaurant-Menu-djnago

python -m venv venv<br>
source venv/bin/activate      # Linux / macOS<br>
venv\Scripts\activate         # Windows

pip install -r requirements.txt

python manage.py migrate<br>
python manage.py runserver

---

## ▶️ Run the Application

python manage.py runserver
