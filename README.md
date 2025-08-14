
# &#x20;Library Management System — Django (TechQRT Assignment)

A lightweight web-based **Library Management System** built with Django. This application enables **Admins** to manage books and student information, and allows **Students** to register, view issued books (with fines), edit their profiles, and change passwords.

---

## &#x20;Features

### &#x20;Admin

* Add, view, and delete books
* View and manage student registrations
* Issue books to students and track returns
* Automatically calculate fines (₹5/day) for overdue books (after 14 days)

### &#x20;Student

* Register and log in
* View and edit profile details
* View list of issued books and corresponding fines
* Change password

---

## &#x20;Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, CSS, Bootstrap
* **Database:** SQLite (default)

---

## &#x20;Local Setup (Demo)

### 1. Clone the Repository

```bash
git clone https://github.com/HarshaVardhanRao/Library-Management-System.git
cd Library-Management-System
```

### 2. Create & Activate Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply Migrations

```bash
python manage.py migrate
```

### 5. Create Admin Superuser

```bash
python manage.py createsuperuser
# Use:
# Username: admin
# Password: admin123
```

### 6. Start the Server

```bash
python manage.py runserver
```

### 7. Open in Browser

Navigate to: `http://127.0.0.1:8000/`

---

## &#x20;Usage Guide

1. **Admin Panel**

   * Log in at `/admin/`
   * Add books, view/delete books and students
   * Issue books and monitor returns/fines

2. **Student Interface**

   * Register via homepage → *Student Registration*
   * Log in and view/edit profile
   * Check issued books, due dates, and fines
   * Change password

---

## &#x20;Project Structure

```
Library-Management-System/
├── library/                 # Django app
│   ├── migrations/
│   ├── static/              # CSS, JS, images
│   ├── templates/           # HTML templates
│   ├── models.py            # Book, Student, IssuedBook models
│   ├── views.py
│   ├── urls.py
│   └── ...
├── media/                   # User-uploaded files
├── db.sqlite3               # Default database file
├── manage.py
└── requirements.txt
```

---

## &#x20;About the Developer

**HarshaVardhanRao**

