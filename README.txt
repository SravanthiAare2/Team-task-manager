# 🧑‍💼 Team Task Manager SaaS

A web-based Team Task Management System built using **Flask, SQLite, Bootstrap, and Python**.  
This application helps teams manage projects, assign tasks, and track progress efficiently with separate **Admin and Member dashboards**.

---

## 🚀 Features

### 🔐 Authentication System
- User Registration (Admin / Member roles)
- Secure Login system
- Password hashing for security
- OTP-based Forgot Password via email

---

### 👤 Member Features
- Personal dashboard with task and project overview
- Create and manage projects
- Add and track tasks under projects
- View task status (Pending / Completed)
- Progress tracking for each project

---

### 🛠️ Admin Features
- Admin dashboard with full control
- View all users, projects, and tasks
- Delete users, projects, and tasks
- Role-based access control
- System monitoring

---

### 📊 Analytics
- Task completion vs pending chart
- User role distribution chart (Admin vs Member)
- Project progress tracking

---

### 📁 Project Management
- Create projects with title, description, and dates
- Add credential type (URL / ID / Certificate upload)
- View project details and progress

---

### 📋 Task Management
- Create tasks linked to projects
- Assign tasks to users
- Update status (Pending / Completed)
- View task details and due dates

---

### 📄 Additional Features
- PDF report generation for projects
- Dark mode toggle in admin panel
- Responsive UI using Bootstrap
- Clean dashboard design

---

## 🧰 Tech Stack

- **Backend:** Flask (Python)
- **Database:** SQLite (SQLAlchemy)
- **Frontend:** HTML, CSS, Bootstrap 5
- **Authentication:** Flask-Login
- **Email Service:** Flask-Mail (SMTP)
- **PDF Generation:** ReportLab
- **Charts:** Chart.js

---

## 📂 Project Structure
TeamTaskManager/
│
├── app.py
├── Procfile
├── requirements.txt
├── runtime.txt
├── README.txt / README.md
│
├── instance/
│   ├── db.sqlite3
│   ├── task.db
│   ├── taskmanager.db
│   └── teamtask.db
│
├── static/
│   └── (CSS, images, uploads if any)
│
├── templates/
│   ├── Home.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── projects.html
│   ├── tasks.html
│   ├── project_detail.html
│   ├── admin_dashboard.html
│   ├── admin analytics.html
│   ├── admin project.html
│   ├── admin task.html
│
└── (Flask App Files)

⚙️ Setup Instructions
Clone the repository:
git clone https://github.com/SravanthiAare2/team-task-manager.git

Install dependencies:
pip install flask flask_sqlalchemy flask_login flask_mail reportlab
Run the application:
python app.py
Open in browser:
http://127.0.0.1:5000/
🎯 Future Improvements
Real-time chat between team members
Notification system
Mobile app version
Advanced analytics dashboard
👩‍💻 Author

Developed by Shravanthi