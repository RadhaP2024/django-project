# 🐍 Beginner Django Project

This is a beginner-friendly web application built using the Django framework.  
The project demonstrates basic Django concepts like models, views, templates, and URL routing.

---

## 🚀 Features

- Basic Django project setup
- URL routing
- Templates rendering
- Simple views
- SQLite database (default)
- Admin panel access

---

## 🛠️ Technologies Used

- Python 3
- Django
- HTML5
- CSS3
- SQLite3

---

## 📂 Project Structure

```
myproject/
│
├── myapp/               # Django application
├── templates/           # HTML files
├── db.sqlite3           # Database file
├── manage.py
└── README.md
```

---

## ⚙️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/project-name.git
cd project-name
```

### 2️⃣ Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
```

Activate it:

**Windows**
```bash
venv\Scripts\activate
```

**Mac/Linux**
```bash
source venv/bin/activate
```

### 3️⃣ Install Django

```bash
pip install django
```

### 4️⃣ Apply Migrations

```bash
python manage.py migrate
```

### 5️⃣ Run the Server

```bash
python manage.py runserver
```

Open your browser and go to:

```
http://127.0.0.1:8000/
```

---

## 👤 Admin Panel (Optional)

Create superuser:

```bash
python manage.py createsuperuser
```

Login at:

```
http://127.0.0.1:8000/admin/
```

---

## 🎯 Purpose of This Project

This project was created to learn:

- Django project structure
- Models, Views, Templates (MVT)
- URL configuration
- Database migration
- Admin panel usage

---

## 📌 Future Improvements

- Add authentication system
- Add CRUD functionality
- Improve UI design
- Deploy project online

---

## 👩‍💻 Author

RADHA

---

⭐ This project is created for learning purposes.
