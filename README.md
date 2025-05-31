# Laguna PHO Record Management System

## 🔍 Project Description

A web-based record management system designed for the Laguna Provincial Health Office (PHO). It allows administrators and coordinators to manage municipalities, user accounts, and system operations. A local logging system was added to enhance accountability and offline auditing.

## 🚀 Features

* User authentication with role-based access (Admin and Coordinator)
* Coordinator account management
* Municipality data listing and creation
* Logging of:

  * Successful login attempts
  * Page visits
  * Account creations
  * Status updates (active, inactive, locked)
  * Email notification attempts

## 🛡️ Enhancement Summary

**Feature Added:** Local User Activity Logging

### 🔧 Description of Enhancement

To improve accountability and traceability, a custom-built logging system was added using a `logger.php` file. It automatically tracks all major user actions. Each entry is recorded in `activity_log.txt` with a timestamp, user role, and full name. The feature is 100% offline and does not require any external connection or services.

### 🔄 How It Works

* Each important PHP file includes `logger.php`
* Actions are logged via `logAction()`
* Example log: `[2025-05-30 11:13:12] [Admin: LAGUNA PHO ADMIN] Visited: Dashboard`

## 🧰 Technologies Used

* PHP 7.4+
* MySQL / phpMyAdmin
* Bootstrap 5
* JavaScript
* XAMPP (Local Server)

## 🎥 Demo Video

📎 [Click here to view]()

## 🧪 How to Run

1. Install XAMPP and run Apache + MySQL
2. Place the `/src/` folder into `htdocs`
3. Import `lpho_db.sql` in phpMyAdmin
4. Open `http://localhost/src/index.php` in your browser

## 👨‍💻 Developer

**Ren Cabreza**
BS Computer Science – LSPU Sta. Cruz

## 📅 Submission Info

**Subject:** CMSC 311 – Software Engineering
**Date:** May 31, 2025
