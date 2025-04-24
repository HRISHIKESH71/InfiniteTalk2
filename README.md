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
---
## 🖼️ Execution of flask project

<h3 align="center">🖼️ /login</h3>
<p align="center">
  <img src="https://github.com/HRISHIKESH71/InfiniteTalk2/blob/main/Images/Screenshot%20(628).png" alt="a" width="700"/>
</p>
<h3 align="center">🖼️ Register</h3>
<p align="center">
  <img src="https://github.com/HRISHIKESH71/InfiniteTalk2/blob/main/Images/Screenshot%20(629).png" alt="a" width="700"/>
</p>

<h3 align="center">🖼️ register successful</h3>
<p align="center">
  <img src="https://github.com/HRISHIKESH71/InfiniteTalk2/blob/main/Images/Screenshot%20(630).png" alt="a" width="700"/>
</p>

<h3 align="center">🖼️ Autosave Entry</h3>
<p align="center">
  <img src="https://github.com/HRISHIKESH71/InfiniteTalk2/blob/main/Images/Screenshot%20(631).png" alt="a" width="700"/>
</p>

<h3 align="center">🖼️ login with credits</h3>
<p align="center">
  <img src="https://github.com/HRISHIKESH71/InfiniteTalk2/blob/main/Images/Screenshot%20(625).png" alt="a" width="700"/>
</p>

<h3 align="center">🖼️ Able to post, View History</h3>
<p align="center">
  <img src="https://github.com/HRISHIKESH71/InfiniteTalk2/blob/main/Images/Screenshot%20(627).png" alt="a" width="700"/>
</p>

<h3 align="center">📚 Stored History</h3>
<p align="center">
  <img src="https://github.com/HRISHIKESH71/InfiniteTalk2/blob/main/Images/Screenshot%20(626).png" alt="a" width="700"/>
</p>

<h3 align="center">📚 Top post on server</h3>
<p align="center">
  <img src="https://github.com/HRISHIKESH71/InfiniteTalk2/blob/main/Images/Screenshot%20(625).png" alt="a" width="700"/>
</p>

---



## 🧑‍💻 Author
- Made by [Hrishikesh Jadhav]
- For suggestions or issues, feel free to open a PR or issue!
