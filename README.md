# Team Task Manager

A Full-Stack Task Management Web Application built using Flask, SQLAlchemy, Bootstrap, and SQLite.  
The application allows teams to create projects, assign tasks, manage progress, and track work efficiently with role-based authentication.

---

# Features

- User Signup & Login Authentication
- Role-Based Access Control (Admin / Member)
- Project Creation & Management
- Task Creation and Assignment
- Task Status Tracking
- Dashboard with Task Overview
- Responsive UI using Bootstrap
- Secure Password Hashing
- Live Deployment

---

# Tech Stack

## Frontend
- HTML
- CSS
- Bootstrap 5
- JavaScript

## Backend
- Flask
- Flask SQLAlchemy
- Flask Login

## Database
- SQLite

## Deployment
- Render / Railway

---

# Folder Structure

```bash
team-task-manager-flask/
│
├── app.py
├── requirements.txt
├── Procfile
├── runtime.txt
│
├── templates/
│   ├── base.html
│   ├── login.html
│   ├── signup.html
│   ├── dashboard.html
│   ├── create_project.html
│   ├── create_task.html
│   ├── my_tasks.html
│
├── static/
│   └── style.css
```

---

# Installation

```bash
pip install -r requirements.txt
python app.py
```

---

# Functionalities

## Admin
- Create Projects
- Create Tasks
- Assign Tasks
- Manage Task Status
- View Dashboard

## Member
- View Assigned Tasks
- Track Task Progress

---

# Dashboard

The dashboard displays:
- Total Tasks
- Completed Tasks
- Pending Tasks
- Task Details

---

# Security Features

- Password Hashing using Werkzeug
- Session-Based Authentication
- Role-Based Route Protection

---

# API Routes

## Authentication
- `/signup`
- `/login`
- `/logout`

## Project Management
- `/create-project`

## Task Management
- `/create-task`
- `/my-tasks`

## Dashboard
- `/dashboard`

---

# Deployment

The application is deployed online for live accessibility and testing.

---

# Future Improvements

- Email Notifications
- Task Priority Levels
- File Uploads
- Search & Filters
- Dark Mode

---

# Author

**Syed Naseera**
