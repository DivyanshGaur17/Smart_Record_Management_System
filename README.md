The Smart Record Management System is a desktop-based application designed to efficiently manage student data and academic records. It provides a user-friendly interface for handling student information, course registrations, and administrative tasks.

This system performs all essential CRUD operations (Create, Read, Update, Delete) and introduces an advanced barcode-based attendance system, making attendance tracking faster and more accurate.

Developed using Java Swing for GUI and integrated with a MySQL database via JDBC, the system ensures seamless data storage and retrieval.

🚀 Features
➕ Add new student records
📷 Barcode-based attendance system
📋 View student details
✏️ Update existing records
❌ Delete student data
📚 Manage course registrations
🔍 Search functionality
🖥️ User-friendly GUI using Java Swing

Generate barcode for each student
Scan barcode to mark attendance
Reduces manual errors and saves time
🛠️ Tech Stack
Programming Language: Java
GUI Framework: Swing
Database Connectivity: JDBC
Database: MySQL
IDE: Apache NetBeans
Server: Apache
🗄️ Database Details
Database Name: student_management (customizable)
Tables Included:
Students
Courses
Registrations
Attendance
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/smart-record-management-system.git
2️⃣ Open Project
Open Apache NetBeans
Import the project
3️⃣ Configure Database
Install MySQL
Create database:
CREATE DATABASE student_management;
Import SQL file (if provided)
4️⃣ Update JDBC Configuration
String url = "jdbc:mysql://localhost:3306/student_management";
String user = "root";
String password = "your_password";
5️⃣ Run the Project
Run the project using NetBeans
📷 Barcode Attendance Workflow
Each student is assigned a unique barcode
Barcode is generated and stored in the system
Scanner reads the barcode during attendance
Attendance is automatically recorded in the database
