# Daily Wage Job Portal 💼

A web-based platform that connects daily wage workers with employers offering temporary and daily employment opportunities. The portal helps workers discover job opportunities and enables employers to post jobs and manage applicants through a simple, user-friendly interface.

## 📌 Project Overview

Finding daily wage employment can be challenging for workers, while employers may struggle to find suitable workers quickly. The Daily Wage Job Portal aims to simplify this process by providing a centralized platform for job discovery, job posting, and worker-employer connections.

## ✨ Features

### 👷 Worker
- User registration and login
- Browse available job opportunities
- Manage worker profile information
- Edit profile details
- Receive job-related notifications

### 🏢 Employer
- Registration and login
- Post job opportunities
- Manage posted jobs
- View applicants and worker information

### 🔐 Admin
- Administrative login
- Dashboard for managing portal information

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Backend | Python, Flask |
| Database | SQLite |
| Version Control | Git, GitHub |

## 📂 Project Structure

```text
Daily-Wage-Job-Portal/
├── app.py
├── db.py
├── schema.sql
├── README.md
├── .gitignore
├── static/
│   ├── css/
│   ├── images/
│   └── js/
└── templates/
    ├── index.html
    ├── login.html
    ├── register.html
    ├── browse_jobs.html
    ├── worker.html
    ├── employer.html
    └── admin_dashboard.html
```

## ⚙️ Installation and Setup

### Prerequisites
- Python 3.x
- pip
- Git (optional)

### 1. Clone the repository

```bash
git clone https://github.com/sureshrathod007/Daily-Wage-Job-Portal.git
cd Daily-Wage-Job-Portal
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
pip install Flask
```

Install any additional packages required by the application.

### 4. Configure the Flask secret key

Set a private secret key in your terminal before running the application. Generate your own secure random value and do not commit it to GitHub.

```powershell
$env:SECRET_KEY = "your-own-random-secret"
```

### 5. Run the application

```bash
python app.py
```

Open the local address shown in the terminal, usually:

http://127.0.0.1:5000

## 📸 Screenshots

Screenshots are not currently included in this repository. Screenshots of the home page, worker dashboard, employer dashboard, job browsing page, and admin dashboard can be added after capturing the running application.

## 🎯 Project Objective

To provide an accessible platform for daily wage workers to discover employment opportunities and help employers connect with potential workers efficiently.

## 👥 Team Members

This group project was collaboratively developed by:

1. **Suresh Rathod**
2. **Vikas Shejul**
3. **Ajay Lonkar**

## 🤝 Project Collaboration

The team worked collaboratively on the planning, design, development, and documentation of the Daily Wage Job Portal.

## 📄 License

No license has been specified yet.
