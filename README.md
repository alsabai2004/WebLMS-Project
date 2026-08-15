🎓 WebLMS

Web Learning Management System

WebLMS is a web-based Learning Management System built with Laravel and designed to simplify the management and delivery of online courses.

The platform provides separate experiences for administrators and students, with tools for managing courses, lessons, enrollments, reviews, users, and learning content.

---

🚀 Overview

WebLMS provides a structured environment for managing an online learning platform.

The current system includes:

- 👨‍💼 Administrator management
- 👨‍🎓 Student accounts and dashboard
- 📚 Course management
- 📖 Lesson management
- 📝 Course reviews
- 🎓 Course enrollment
- 👤 User management
- 🔐 Authentication and account management
- 📊 Administrative dashboard
- 🗄️ Database migrations and seeders
- 🧪 Automated application tests

---

✨ Current Features

👨‍💼 Administration

Administrators can:

- Manage users
- Create and manage courses
- Create and manage lessons
- Monitor course enrollments
- Manage course reviews
- Manage administrator profile
- Access the administration dashboard

👨‍🎓 Student Experience

Students can:

- Create an account
- Sign in securely
- Browse available courses
- Enroll in courses
- Access enrolled course content
- View lessons
- Submit course reviews
- Manage their profile

📚 Course Management

WebLMS supports:

- Course creation
- Course editing
- Course descriptions
- Course thumbnails
- Lesson organization
- Student enrollment
- Course reviews

🔐 Authentication

The application includes:

- Registration
- Login
- Logout
- Password reset
- Password confirmation
- Email verification
- Password updates
- Profile management

---

🏗️ Application Structure
```
WebLMS-Project/
│
├── app/
│   ├── Http/
│   │   ├── Controllers/
│   │   │   ├── Admin/
│   │   │   ├── Auth/
│   │   │   └── Student/
│   │   ├── Middleware/
│   │   └── Requests/
│   │
│   ├── Models/
│   ├── Policies/
│   ├── Providers/
│   └── View/
│
├── database/
│   ├── factories/
│   ├── migrations/
│   └── seeders/
│
├── resources/
│   ├── css/
│   ├── js/
│   └── views/
│
├── routes/
│   ├── admin.php
│   ├── auth.php
│   ├── student.php
│   └── web.php
│
├── public/
├── tests/
├── composer.json
├── package.json
└── vite.config.js
```
---

| Technology | Purpose |
|---|---|
| PHP | Backend programming |
| Laravel | Web application framework |
| Laravel Blade | Server-side UI |
| Laravel Breeze | Authentication |
| MySQL / SQLite | Database support |
| Tailwind CSS | Interface styling |
| JavaScript | Frontend interactions |
| Vite | Frontend asset development |
| PHPUnit | Application testing |
| Composer | PHP dependency management |
| npm | JavaScript dependency management |

---

🗄️ Main Data Models

The current application includes the following main models:

- User
- Course
- Lesson
- Review

The database also contains relationships for:

- Course enrollments
- Lesson access
- Course reviews
- User accounts
- Course content

---

⚙️ Installation

1. Clone the repository

git clone https://github.com/alsabai2004/WebLMS-Project.git
cd WebLMS-Project

2. Install PHP dependencies

composer install

3. Install frontend dependencies

npm install

4. Create the environment file

cp .env.example .env

5. Generate the application key

php artisan key:generate

6. Configure the database

Update the database configuration in ".env".

For SQLite, create the database file and configure:

DB_CONNECTION=sqlite

7. Run migrations and seeders

php artisan migrate --seed

8. Build frontend assets

For development:

npm run dev

9. Start the Laravel server

php artisan serve

The application will be available at:

http://localhost:8000

---

🔑 Demo Account

The seeded administrator account is currently configured as:

Email: admin@weblms.local
Password: password

«Change the default credentials before deploying WebLMS to a production environment.»

---

🧪 Testing

Run the Laravel test suite with:

php artisan test

---

🔒 Security

WebLMS uses Laravel's built-in security mechanisms for:

- Authentication
- Password hashing
- CSRF protection
- Request validation
- Authorization policies
- Session management
- Email verification

---

🗺️ Development Roadmap

WebLMS is being actively developed. Planned improvements include:

- [ ] Instructor / Teacher accounts
- [ ] Instructor dashboard
- [ ] Course progress tracking
- [ ] Course completion tracking
- [ ] Online quizzes
- [ ] Questions and assessments
- [ ] Certificates
- [ ] Learning statistics
- [ ] Advanced course search and filtering
- [ ] Notifications
- [ ] File and learning-material management
- [ ] Improved administration dashboard
- [ ] REST API
- [ ] Automated CI/CD
- [ ] Docker support

---

🎯 Project Goals

The goal of WebLMS is to evolve into a complete and flexible learning management platform capable of supporting:

Administrators → Instructors → Students → Courses → Lessons → Assessments → Progress → Certificates

The project will continue to evolve through iterative development, testing, security improvements, and new educational features.

---

👨‍💻 Project

(WebLMS) Web Learning Management System

Developed and maintained by Eng\ Mohammed Najeeb Abd-Ulrazzaq Al-Sabai 

GitHub :

https://github.com/alsabai2004
---

📄 License

See the "LICENSE" file for the licensing terms applicable to this project.
