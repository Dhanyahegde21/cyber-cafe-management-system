# cyber-cafe-management-system
A management system for running a cyber cafe
# ☕ Cyber Cafe Management System

A **Cyber Cafe Management System** is a web-based application designed to automate and manage daily cyber cafe operations such as user management, computer allocation, billing, payments, and invoice generation.

---

## 📌 Project Overview

This project helps cyber cafe administrators efficiently manage customers, systems, and payments while reducing manual work and errors.

---

## 🎯 Objectives

* Automate cyber cafe operations
* Maintain user and computer records
* Calculate usage-based billing
* Generate invoices and payment reports
* Provide secure admin access

---

## 🛠️ Technologies Used

* **Frontend**: HTML, CSS, Bootstrap
* **Backend**: PHP
* **Database**: MySQL
* **Server**: WAMP / XAMPP

---

## 👥 User Roles

### 1. Admin

* Manage users
* Manage computers
* View payments and invoices
* Control overall system

### 2. User (Customer)

* Register / Login
* Use allocated computer
* View usage and invoice

---

## 🔐 Admin Login Credentials (Default)

> **Username:** `admin`
>
> **Password:** `Admin@123`

⚠️ *Note: Change default credentials after first login for security.*

---

## 🧩 Modules Description

### 1. Admin Module

* Admin login authentication
* Add / update / delete users
* Add / manage computer systems
* View all transactions
* Generate reports

### 2. User Module

* User registration & login
* View allocated computer details
* Track usage time
* View invoice details

### 3. Computer Module

* Computer ID and system details
* Hardware details (keyboard, mouse, monitor)
* System availability status

### 4. Payment Module

* Calculate usage cost
* Store payment details
* Payment status tracking

### 5. Invoice Module

* Auto-generate invoices
* Display user name, system used, time, and cost
* Printable invoice format

---

## 🗄️ Database Design

**Main Tables Used:**

* `usermaster`
* `userdetails`
* `computers`
* `computer_details`
* `payments`
* `invoice

Primary and Foreign key relationships are maintained for data integrity.

---

## ⚙️ Installation & Setup (Step-by-Step)

### Step 1: Install Server

* Install **WAMP** or **XAMPP** on your system

### Step 2: Copy Project Files

* Copy the project folder to:

  * `www` (WAMP) or
  * `htdocs` (XAMPP)

### Step 3: Database Setup

1. Open **phpMyAdmin**
2. Create a database named:

   ```
   cybercafe_db
   ```
3. Import the provided SQL file

### Step 4: Configure Database Connection

* Open `config.php`
* Update database credentials if needed

### Step 5: Run the Project

* Open browser
* Type:

  ```
  http://localhost/cybercafe
  ```

---

## ✅ Features

* Secure login system
* Role-based access
* Real-time billing calculation
* User-friendly interface
* Modular and scalable design

---

## 🚀 Future Enhancements

* Online payment integration
* Session-based auto logout
* Graphical reports
* SMS / Email notifications

---

## 📚 Conclusion

The **Cyber Cafe Management System** simplifies cafe operations by providing a centralized, secure, and efficient platform. It reduces paperwork, improves accuracy, and enhances customer experience.



⭐ *This project is suitable for academic submission and practical implementation.*

