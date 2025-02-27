# 📌 Attendance Management System

## 📖 Introduction
The **Attendance Management System** is a web-based application designed to streamline the process of student attendance tracking in educational institutions. This system replaces traditional manual attendance methods with an efficient and automated solution. ✅

## 🌟 Features
- 🔐 Secure login system for faculty
- 📌 Student attendance marking with automated percentage calculation
- 🔄 Real-time database updates
- 📊 Monthly and consolidated attendance reports
- 🖥️ User-friendly interface with responsive design

## 🛠️ Technologies Used
### 🎨 Frontend:
- HTML 📝
- CSS 🎨
- JavaScript ⚡
- Bootstrap 🎭

### 🖥️ Backend:
- PHP 🖥️
- MySQL 🗄️

### 🌐 Server:
- XAMPP (Apache, MySQL, PHP, and Perl) 🚀

## 🖥️ System Requirements
### 💾 Hardware:
- Processor: ⚙️ Intel i3 or higher
- RAM: 🧠 4 GB or more
- Storage: 💾 40 GB HDD or SSD

### 🖥️ Software:
- OS: 🏁 Windows 7/10 or Linux
- XAMPP Server 🛠️
- Visual Studio Code (Recommended for Development) ✨

## 🚀 Installation and Setup
1. **📥 Clone the Repository**:
   ```sh
   git clone https://github.com/ShaliniKanniyappan/AttendanceApp.git
   ```
2. **🛠️ Install XAMPP and Start Services**:
   - Download and install [XAMPP](https://www.apachefriends.org/download.html) 🌍
   - Start Apache and MySQL services ▶️

3. **📌 Setup the Database**:
   - Open `phpMyAdmin` 🎛️
   - Create a new database named `attendance_db` 🗄️
   - Import the `attendance_db.sql` file from the project 📂

4. **🔧 Configure Database Connection**:
   - Open `database.php` 🛠️
   - Update the following details:
     ```php
     private $servername = "localhost";
     private $username = "root";
     private $password = "";
     private $dbname = "attendance_db";
     ```

5. **🚀 Run the Application**:
   - Place the project folder inside `htdocs` directory (if using XAMPP) 🗂️
   - Open a browser and visit `http://localhost/attendance-app` 🌍

## 📌 Usage
- **🔑 Login:** Faculty members can log in using their credentials.
- **📝 Mark Attendance:** Select a subject and mark students as present or absent.
- **📊 View Reports:** Generate attendance reports for analysis.

