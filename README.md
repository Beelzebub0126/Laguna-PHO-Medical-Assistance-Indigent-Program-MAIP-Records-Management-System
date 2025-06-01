# Laguna PHO Record Management System

## 📌 Project Title

Laguna PHO Record Management System with Local Activity Logging

## 📝 Short Description

This project is a web-based information system for the Laguna Provincial Health Office (PHO) designed to manage user accounts and municipality data. An automation and security enhancement was added to log all user activities to a local file, allowing offline monitoring of actions for security and transparency.

## 🚀 Features Added / Enhanced

* ✅ Local activity logging system (via `logger.php`)
* ✅ Page visits
* ✅ Functionality — logs saved in `activity_log.txt`
* ✅ Coordinator and municipality management

## 🧰 Technologies Used

* PHP 7.4+
* MySQL / phpMyAdmin
* Bootstrap 5
* HTML5, CSS3
* JavaScript (vanilla)
* XAMPP (Apache + MySQL)

## 🛠 Installation Instructions

1. Download and install **XAMPP**.
2. Copy the `/src/` folder into the `htdocs` directory.
3. Import `lpho_db.sql` into **phpMyAdmin**.
4. Run Apache and MySQL using the XAMPP Control Panel.
5. Open your browser and go to: `http://localhost/src/lagunapho_Security_and_Automation_FINAL_UPDATED`

## ▶️ How to Use / Run the Project

* Log in as either **Admin** or **Coordinator**.
* Admins can:

  * Add and manage Coordinator accounts
  * Add new municipalities
  * Change account statuses
* All actions (logins, updates, form submissions) are recorded in `activity_log.txt`.

## 🎥 Demo Video Link

[Watch the demo here](https://drive.google.com/drive/folders/12f8rB9SiBqte1LW72WeA7FEHnPDebPdX?usp=drive_link)

## 📁 Folder Structure Description

```
/lagunapho_Security_and_Automation/
├── /src/               ← PHP, JS, CSS, assets
├── /docs/              ← SRS.pdf, TechnicalDoc.pdf
├── activity_log.txt    ← auto-generated log file
├── README.md
```

## 👨‍💻 Contributors

**Ren Cabreza**
BS Computer Science – LSPU Sta. Cruz
