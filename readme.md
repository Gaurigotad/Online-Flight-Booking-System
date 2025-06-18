# ✈️ Online Flight Booking System

A complete web-based flight booking platform developed using **PHP**, **MySQL**, **HTML**, **CSS**, and **JavaScript**. This system allows users to search, book, and manage flights seamlessly, and provides admins with robust tools to manage flight schedules and user bookings.

## 🚀 Features

### 👤 User Side:
- 🌍 Browse and search flights by source, destination, and date
- 📆 View flight details and schedules
- 🪪 User registration and secure login
- 🧾 Booking confirmation with reference ID
- 📩 Email-based password reset system
- 🗃 View personal bookings and history

### 🛠️ Admin Side:
- ✈️ Add, edit, or delete flights
- 📋 View and manage all bookings
- 🧑‍💼 Manage users
- 📊 Filter flights by airline, date, source, etc.

---

## 🛠 Tech Stack

| Frontend | Backend | Database | Others |
|----------|---------|----------|--------|
| HTML5    | PHP     | MySQL    | PHPMailer |
| CSS3     |         |          |         |
| JavaScript |       |          |         |

---

## ⚙️ How to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Gaurigotad/Online-Flight-Booking-System
   cd Online-Flight-Booking-System
2. Import the Database  
 • Open phpMyAdmin
 • Create a new database (e.g., ofbms)  
 • Import the SQL file from the db folder
  
3. Configure Database Connection  
 • Edit helpers/init_conn_db.php with your DB credentials

4. Run on Localhost  
 • Place the folder in your web server directory (htdocs for XAMPP) 
 • Start Apache and MySQL  
 • Visit: http://localhost/Online-Flight-Booking-System

📌 Project Structure
  📁 Online-Flight-Booking-System
  ├── 📂 assets/           # CSS, JS, Images
  ├── 📂 includes/         # Header, footer, etc.
  ├── 📂 helpers/          # DB connection, validation, etc.
  ├── 📂 admin/            # Admin dashboard and features
  ├── 📂 user/             # User booking features
  ├── 📂 db/               # Database SQL files
  ├── index.php           # Homepage
  ├── login.php           # User login
  └── ...

📧 Contact
Have any suggestions or want to contribute?
📬 Reach out via Gaurigotad

## **Default Admin Access**
**username: admin**
**password: admin123**
