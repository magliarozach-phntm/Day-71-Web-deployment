# Flask Blog Web Application

A production-ready blog application built with Flask and deployed on Render.

**Live Demo:** https://day-71-web-deployment-xon8.onrender.com

---

## Features

- User registration and authentication
- Secure password hashing
- User login/logout with Flask-Login
- Create, edit, and delete blog posts
- Rich text editing using CKEditor
- Comment system
- User avatars via Gravatar hashing
- Responsive Bootstrap interface
- Production deployment on Render

---

## Built With

- Python
- Flask
- SQLAlchemy
- SQLite / PostgreSQL (deployment)
- WTForms
- Flask-Login
- Bootstrap
- CKEditor
- Gunicorn
- Render

---

## Installation

Clone the repository:

```bash
git clone https://github.com/magliarozach-phntm/YOUR_REPO.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file:

```text
SECRET_KEY=your_secret_key
DATABASE_URL=your_database_url
```

Run locally:

```bash
python main.py
```

---

## Deployment

The application is deployed using Render.

Deployment includes:

- Gunicorn production server
- Environment variables
- Automatic deployments from GitHub
- HTTPS hosting

---

## Future Improvements

- User profile pictures
- Password reset
- Search functionality
- Categories and tags
- Markdown support
- Email notifications
- Rich admin dashboard

---

## What I Learned

This project helped me gain experience with:

- Flask application structure
- SQLAlchemy relationships
- Authentication vs. authorization
- Password hashing
- Production deployment
- Git and GitHub workflows
- Environment variable management
- Debugging production issues

## Author

**Zachary Magliaro**

GitHub:
https://github.com/magliarozach-phntm
