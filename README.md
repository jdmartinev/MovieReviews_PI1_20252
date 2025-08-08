<!-- Project badges -->
[![Python](https://img.shields.io/badge/python-3.12-blue)](https://www.python.org/)
[![Django](https://img.shields.io/badge/django-5-green)](https://www.djangoproject.com/)
[![Bootstrap](https://img.shields.io/badge/bootstrap-5-purple)](https://getbootstrap.com/)

# Movie Reviews 📽️

_Share your short opinions on classic and contemporary films in a snap._

---

## 📑 Table of Contents

1. [Overview](#overview)  
2. [Features](#features)  
3. [Tech Stack](#tech-stack)  
4. [Quick Start](#quick-start)  
5. [Project Structure](#project-structure)  
6. [Contact](#contact)  

---

## 📝 Overview

Movie Reviews is a **lightweight Django web application** where cinephiles can:

- Browse and search for movies by title.  
- Post, edit, or delete **one** review per film.  
- Mark films as “Watch Again” favorites.  
- Catch up on the latest site news and developer updates.  

Whether you’re revisiting a timeless classic or discovering a hidden gem, Movie Reviews makes sharing your thoughts quick and fun.

---

## ✨ Features

| Category           | What it does                                              |
| ------------------ | --------------------------------------------------------- |
| 🎬 **Browse**      | List all movies with poster, synopsis & detail page.      |
| ✍️ **Reviews**     | Authenticated users can create, edit or delete one review. |
| 🔐 **Auth**        | Secure email/password sign-up, log-in & log-out.          |
| 🔎 **Search**      | Find titles by exact or partial match.                   |
| 🌟 **Favourites**  | “Watch Again” button to bookmark your must-revisit films. |
| 📰 **News**        | Timeline of the latest site updates, newest first.        |
| 🧑‍💻 **About**     | Meet the developer team behind the app.                   |
| 🛣️ **Roadmap**     | Upcoming: semantic search (ChatGPT), AWS S3 media, dark mode. |

---

## 🛠️ Tech Stack

- **Language & Framework**: Python 3.12 · Django 5  
- **Frontend**: Bootstrap 5  
- **Database**: SQLite (swap for PostgreSQL/MySQL in production)  
- **Image Handling**: Pillow ≥ 10  

---

## 🚀 Quick Start

1. **Clone the repo**  
```
git clone https://github.com/paolavallejo/MovieReviews_PI1_20252.git
cd MovieReviews_PI1_20252
```
Set up virtual environment

```bash

python3.12 -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate

```
Install dependencies
```

pip install -r requirements.txt
```
Apply migrations & create superuser

```bash

python manage.py migrate
python manage.py createsuperuser
```
Run the development server

```bash

python manage.py runserver
Open your browser at http://127.0.0.1:8000/
```

📂 Project Structure
```bash

├── movie/             # Core app (models, views, templates)
├── moviereviews/      # Django project (settings, URLs)
├── media/             # Uploaded posters (runtime)
├── manage.py          # CLI entry point
└── requirements.txt   # Pinned dependencies
```


📬 Contact

Paola Vallejo (@paolavallejo)

José Alejandro Duque (@joseduquep)

Feel free to open an issue or drop us a message!
