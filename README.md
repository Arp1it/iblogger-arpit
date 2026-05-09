# iBlogger

A clean and minimal blogging platform built with Django where users can read, explore, and manage blog content through a simple and responsive interface.

Built using Django with a clean UI powered by TailwindCSS and Django templates.

---

## 🚀 Features

* ✍️ Create and manage blog posts
* 📖 Read blogs with a clean UI
* 🖼️ Image support for blog content
* 📱 Responsive design
* ⚡ Fast and lightweight interface
* 🎨 Simple and beginner-friendly project structure
* 🗂️ Organized templates and static files

---

## 🛠️ Tech Stack

### Backend

* Python
* Django

### Frontend

* HTML5
* CSS3
* TailwindCSS (CDN based) fileciteturn0file0
* Django Templates

### Database

* SQLite3

---

## 📂 Project Structure

```bash
iblogger-arpit/
│
├── blog/               # Blog application
├── templates/          # HTML templates
├── static/             # Static files (CSS, JS, images)
├── media/              # Uploaded media files
├── mypr/               # Project configuration
├── manage.py
├── db.sqlite3
├── templates/
├── static/
└── .gitignore
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Arp1it/iblogger-arpit.git
cd iblogger-arpit
```

### 2️⃣ Create Virtual Environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

### 3️⃣ Install Django

```bash
pip install django
```

> Note: This project currently does not include a `requirements.txt` file.

---

### 4️⃣ Run Migrations

```bash
python manage.py migrate
```

---

### 5️⃣ Start the Development Server

```bash
python manage.py runserver
```

Now open:

```bash
http://127.0.0.1:8000/
```

---

## 🎨 UI & Styling

The project uses TailwindCSS through CDN integration directly inside Django templates for fast styling and responsive layouts. fileciteturn0file0

Features in the UI include:

* Responsive navigation bar
* Dynamic authentication buttons
* Styled alert/message system
* Responsive footer sections
* Tailwind utility-based layouts
* Clean dark-themed header design

---

## 👨‍💻 Author

Created by [Arpit Jaiswal GitHub](https://github.com/Arp1it?utm_source=chatgpt.com)
