# 🧑‍🎓 Student Study Portal

A Django-based web application that acts as a centralized study assistant for students. It offers tools like note-taking, to-do management, dictionary, YouTube search, Wikipedia summary, book listing, homework tracker, and unit converters — all in one dashboard.

---

## 🚀 Features

- 📚 Notes creation, detail view, and deletion  
- ✅ To-do list with task completion tracking  
- 🧮 Unit converter (Length & Mass)  
- 📖 Book search using Google Books API  
- 🎓 Homework management  
- 🔍 Dictionary word lookup  
- 🎥 YouTube video search  
- 🌐 Wikipedia article summaries  
- 🔐 User registration, login, logout, and profile  

---

## 📂 Project Structure

```
studentstudyportal/
├── dashboard/              # Main app
│   ├── templates/          # HTML templates
│   ├── static/             # Static files (CSS, images)
│   ├── migrations/         # DB schema migrations
│   └── views.py, models.py # Core logic
├── studentstudyportal/     # Django project settings
├── db.sqlite3              # Local database (excluded via .gitignore)
├── manage.py
└── .gitignore
```

---

## ⚙️ Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/PriyanshuVe/Student-Study-Portal.git
   cd Student-Study-Portal
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   venv\Scripts\activate  # On Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations and run server**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   python manage.py runserver
   ```
   
---

## 🛡️ License

This project is licensed under the MIT License - feel free to use or contribute!

---

## 👨‍💻 Author

**Priyanshu Verma**  
[GitHub](https://github.com/PriyanshuVe)
