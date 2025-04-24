# InfiniteTalk

## 🧠 InfiniteTalk - Flask Discussion & Learning Platform

TaskHub is a role-based Flask web app that allows **users** to sign up. Learners can explore content, post discussions, and comment on ideas.

## Visit to below link to view live working of InfiniteTalk project
✅ click-here[]

## 🚀 Features

- 🔐 User Authentication (Register/Login)
- 🧭 Role Selection (Learner or Guider)
- 📝 Post discussions and comments
- 🔍 View top posts sorted by comment count
- 🍪 Profile info stored in cookies (Learner mode)
- 📊 Guider dashboard to manage course details
- 🕵️ Toggle comments on top posts
- 📅 Timestamps on posts & comments
- 📌 Real-time form validation using Flask-WTF

---

## 🏗️ Tech Stack

- **Flask**
- **Flask-Login**, **Flask-WTF**, **SQLAlchemy**
- **Jinja2 templating**
- **SQLite** (default, can be upgraded)
- **Bootstrap** (for layout)
- **Render** (for deployment)

---

## App Flow
 ```bash
      flask_login_register/
      │
      ├── app/
      │   ├── __init__.py        ← Initializes the Flask app & extensions
      │   ├── routes.py          ← Routes (views)
      │   ├── models.py          ← SQLAlchemy models
      │   ├── forms.py           ← WTForms forms
      │
      ├── templates/
      │   ├── base.html
      │   ├── register.html
      │   ├── login.html
      │   ├── confirm.html
      │   └── dashboard.html
      │
      ├── run.py                 ← Entry point
      └── requirements.txt       ← Dependencies (optional)
```
## 🧑‍💻 Author
- Made by [Hrishikesh Jadhav]
- For suggestions or issues, feel free to open a PR or issue!
