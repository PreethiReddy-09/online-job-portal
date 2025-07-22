
# Online Job Portal

A demo web application where users can register as job providers or job seekers, post and apply for jobs, and explore job listings—all powered by PHP, MySQL, and Bootstrap.

---

## 🧩 Features

- **User Registration & Authentication**  
  - Register and log in as **Job Provider** or **Job Seeker**  
  - Secure login/logout flow

- **Job Management (for Providers)**  
  - Post new job listings  
  - View and manage posted jobs  
  - View applications from job seekers

- **Job Exploration (for Seekers)**  
  - Browse, filter, and view detailed job listings  
  - Apply directly through the site

- **Admin Tools**  
  - Explore lists of job seekers and providers  
  - Manage user profiles and uploaded documents

---

## ⚙️ Tech Stack

- **Frontend:**  
  - HTML5 / CSS3  
  - JavaScript (dynamic interactions)  
  - Bootstrap (layout & responsive design)

- **Backend:**  
  - PHP (server-side scripting)  
  - MySQL (via XAMPP)

---

## 💾 Setup & Installation

1. **Install XAMPP** (includes Apache and MySQL)  
2. Launch **Apache** and **MySQL** via XAMPP control panel  
3. Clone or download this repository and extract to:  
   ```  
   C:\xampp\htdocs\OnlineJobPortal  
   ```  
4. Open **phpMyAdmin** (`http://localhost/phpmyadmin`)  
5. Create a new database named `onlineJobPortal`  
6. Import the SQL file located at:  
   ```
   OnlineJobPortal/Database/job_portal.sql
   ```  
7. Open your browser and visit:  
   ```
   http://localhost/OnlineJobPortal
   ```

---

## 📸 Screenshots

*(Include captions and relevant screenshots here to showcase login, job posting, job browsing, dashboard views.)*

---

## 🛠️ Project Structure

```
├── app/                       # Core application logic  
├── bootstrap/                # Initialization & configs  
├── constants/                # Config constants (DB, paths, etc.)  
├── css/                      # Stylesheets  
├── js/                       # JavaScript scripts  
├── employee/                 # Job seeker pages  
├── employer/                 # Job provider pages  
├── mail/                     # Mailing utilities  
├── Database/                 # job_portal.sql file here  
├── *.php                     # Entry points (login.php, register.php, explore-job.php, etc.)  
└── README.md
```

---

## 🔗 Useful Endpoints

- `register.php` – signup for seeker or provider  
- `login.php` / `logout.php` – authentication flow  
- `explore-job.php` – browse jobs  
- `job-list.php` – provider’s job listings  
- `apply` – attach resume, view application statuses  
- `view-attachment.php` – view uploaded documents  

---

## 🤝 Contributing

This is a demo project—feel free to fork and enhance it! Suggested improvements:

- Add file upload validation (e.g., restrict file types and size)  
- Implement richer filtering/searching for jobs (location, categories, keywords)  
- Add email notifications upon application submission  
- Improve UI/UX with better Bootstrap layout and modals

---

## 📄 License

This project is open-source. Customize, adapt, and distribute as you wish. Attribution appreciated!

---

### Enjoy using or extending this job portal?  
Drop a star ⭐ on the repo, and feel free to share your contributions or feedback!
