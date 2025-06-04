# 🏠 Real Estate Management System (Full Stack Project)

This is a full-stack real estate management system developed using **React (Vite)** for the frontend and **PHP + MySQL** for the backend. It allows admins and agents to manage properties, messages, images, and more through a dashboard. It also supports user-facing features like browsing listings and contacting agents.

---

## 🔧 Technologies Used

- Frontend: React + Vite, Tailwind CSS
- Backend: PHP (REST API)
- Database: MySQL
- Server: XAMPP (Apache & MySQL)

---

## 📁 Folder Structure
estate/
├── Backend/ ← PHP API files
│ └── api/
│ └── *.php ← All backend PHP files (CRUD, auth, image upload, etc.)
├── db/
│ └── estate_db.sql ← MySQL database dump file
├── public/ ← Public assets
├── src/ ← React frontend components
├── .gitignore
├── README.md
├── package.json
├── vite.config.js


---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/MadhushanSathsara/alfa-lands.git
cd estate
```


---
### 2. Install frontend dependencies

```bash
npm install
```
### 3. Start the frontend (React + Vite)

```bash
npm run dev

```
The frontend will be available at:
➡️ http://localhost:5173/

### 4. Set up the backend
1.Install XAMPP if not already: https://www.apachefriends.org/

2.Move the project to your XAMPP htdocs folder:

```makefile
C:\xampp\htdocs\estate
```
3.Start Apache and MySQL from the XAMPP Control Panel.

4.Access backend API via:

```bash
http://localhost/estate/Backend/api/

```
### 5. Import the MySQL database

1.Open http://localhost/phpmyadmin

2.Create a new database: estate

3.Click Import tab

4.Choose the file:
    
 ```bash
db/estate.sql
 ```
5.Click Go to import the database.

### 6. Update PHP config (if needed)
Make sure your PHP files in /Backend/api point to the correct database name and credentials in db.php:

```php
$host = "localhost";
$username = "root";
$password = "";
$dbname = "estate_db"; // This must match your imported DB
```
    



