# bookstore-api#
📚 Bookstore Management System - REST API

A RESTful API built using Django and Django REST Framework for managing a bookstore system with authentication, role-based access, and order management.

---

## 🚀 Features

- 🔐 JWT Authentication (Login / Register)
- 👤 Custom User Model (Admin & Customer roles)
- 📘 CRUD Operations for Books
- 🛒 Order Management System
- 📄 API Documentation using Swagger
- 🔎 Filtering & Search Functionality

---

## 🛠 Tech Stack

- Python
- Django
- Django REST Framework (DRF)
- Simple JWT
- drf-yasg (Swagger Documentation)
- SQLite (Default Database)

---

## 📂 Project Structure
bookstore-api/
│
├── config/ # Project settings & main URLs
├── users/ # Custom user app
├── books/ # Books management app
├── manage.py
├── requirements.txt
└── README.md

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/susmitakolya/bookstore-api.git
cd bookstore-api
2️⃣ Create Virtual Environment
python -m venv venv
venv\Scripts\activate   # Windows
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run Migrations
python manage.py makemigrations
python manage.py migrate
5️⃣ Run Server
python manage.py runserver

Server will run at:

http://127.0.0.1:8000/
🔑 API Endpoints
👤 Users

POST /api/users/register/ – Register user

POST /api/users/login/ – Login (JWT Token)

📘 Books

GET /api/books/ – List all books

POST /api/books/ – Create book (Admin only)

PUT /api/books/<id>/ – Update book

DELETE /api/books/<id>/ – Delete book
🛒 Orders

Create Order

View Orders
📄 Swagger Documentation

After running server, open:

http://127.0.0.1:8000/swagger/

Interactive API documentation will appear.

You can test APIs directly from browser.
🔎 Key Features Implemented

✔ Custom User Model
✔ Role-based Permission
✔ JWT Authentication
✔ Search & Filtering
✔ Swagger Documentation
✔ Clean Project Structure

🎯 Future Improvements

Pagination

PostgreSQL Database

Deployment on Render

Docker Support
#Author

Susmita Kolya
GitHub: https://github.com/susmitakolya
