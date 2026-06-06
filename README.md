# 🏥 ClinicDesk - Clinic Management System

**ClinicDesk** is a robust, web-based management platform for medical clinics. It streamlines operations by connecting Administrators, Doctors, and Patients in one secure environment.

## 🌟 Key Features
- **Multi-Role Dashboards:** Custom views for Admins, Doctors, and Patients.
- **Smart Appointment Booking:** Prevents double-booking and schedule conflicts.
- **Prescription Management:** Secure PDF upload and download for medical records.
- **User Profiles:** Support for profile pictures (Avatars) and full account management.
- **Security First:** Protected against CSRF, SQL Injection, and unauthorized access.
- **Responsive UI:** Modern design using AdminLTE 3 & Bootstrap.

## 🛠️ Tech Stack
- **Backend:** PHP 8.x (OOP & MVC Pattern)
- **Database:** MySQL / MariaDB
- **Frontend:** HTML5, CSS3, JS (jQuery), AdminLTE 3

## 🚀 Installation Guide
1. **Clone the Project:** Move the folder to your `htdocs` directory.
2. **Database Setup:**
   - Open PHPMyAdmin and create a database named `clinicdesk_db`.
   - Import the `clinicdesk_db.sql` file provided in the root folder.
3. **Configuration:**
   - Check `config/database.php` to ensure your DB credentials (host, user, pass) are correct.
4. **Run:**
   - Open your browser and go to `http://localhost/clinicdesk`.

## 🔐 Default Credentials
- **Admin Email:** `admin@clinic.local`
- **Password:** `Admin@1234`

## 📝 License
This project was developed for educational purposes as a Final Project.
