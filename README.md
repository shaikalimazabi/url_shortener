# Flask URL Shortener

A simple and efficient **URL Shortener web application** built using Flask and SQLite.  
The application allows users to convert long URLs into short links, track visit counts, and manage URLs through a clean and intuitive interface.

---

## 🚀 Live Demo
https://url-shortener-1el2.onrender.com

---

## 🧠 About the Project
This project provides a basic implementation of a URL shortening service similar to popular platforms.  
Users can generate short URLs, use them for redirection, and monitor how many times each link has been accessed.

---

## ✨ Features
- Convert long URLs into short links
- Redirect users using generated short codes
- Track visit counts for each shortened URL
- Delete URLs when no longer needed
- Custom 404 error handling
- Clean and minimal user interface

---

## 🧰 Tech Stack
- Python
- Flask
- SQLite
- Jinja2
- HTML & CSS
- Gunicorn
- Render

---

## 📂 Project Structure
url_shortener/
├── app.py
├── models.py
├── templates/
│ ├── index.html
│ └── 404.html
├── url.db
└── requirements.txt

---

## ▶️ How to Run Locally

### Install dependencies
pip install -r requirements.txt
### Run the application
python app.py

### Open in browser
http://127.0.0.1:5000

### 📌 Learning Outcomes

Built REST-style routes using Flask

Implemented CRUD operations with SQLite

Used Jinja2 for dynamic template rendering

Handled redirects and custom error pages

Deployed a Python web application to production

### 👤 Author

Shaik Alima Zabi
GitHub: https://github.com/shaikalimazabi
