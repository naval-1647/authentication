# Django Auth System 🔐

This is a simple Django project that implements user authentication — including registration, login, logout, and a protected home page.

## 📁 Project Structure

auth_system/
├── accounts/
│ ├── migrations/
│ ├── templates/
│ │ └── accounts/
│ │ ├── login.html
│ │ ├── register.html
│ │ └── home.html
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── models.py
│ ├── tests.py
│ ├── urls.py
│ └── views.py
├── auth_system/
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── db.sqlite3
└── manage.py


---

## 🚀 Features

- ✅ User Registration
- ✅ User Login
- ✅ User Logout
- ✅ Login Required Home Page
- ✅ Django Messages Framework

---

## 🛠 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/django-auth-system.git
cd django-auth-system
