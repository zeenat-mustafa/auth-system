# auth-system
This project contains Full Stack Login and Register Form with User and Admin Page using HTML CSS Javascript PHP and MySQL Database

## Project Description
The key features are
- User registration & login system
- Secure password storage (hashing)
- Basic session management
- MySQL database

## 📦 Setup Guide (XAMPP)

1. **Import the database**:
   - Open phpMyAdmin (`http://localhost/phpmyadmin`)
   - Click **New** → Name: `users_db` → Create
   - Click **Import** → Select `database/users_db.sql` → **Go**

2. **Configure `config.php`** (if needed):
   ```php
   $conn = new mysqli("localhost", "root", "", "users_db");
   ```
   *(Default XAMPP settings already match this!)*  