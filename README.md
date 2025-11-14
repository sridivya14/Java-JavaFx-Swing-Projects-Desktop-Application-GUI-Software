Stadium Management System

A comprehensive Java-based application designed to manage stadium operations efficiently. The system includes features for ticket booking, event scheduling, staff management, and seat allocation, offering a user-friendly interface with a structured backend.

# Features
1. Ticket Booking
Book tickets for upcoming matches or events
Check seat availability in real time
Generate booking confirmations

2. Seat Management
View stadium seating layout
Mark seats as booked, available, or blocked
Manage seat categories (VIP, Premium, Regular)

3. Event Management
Add, update, or remove stadium events
Maintain event schedules and timings
Track event history

4. Staff Management
Add and manage staff records
Assign staff roles during events
Maintain attendance logs

5. Admin Panel
Secure login system
Controls all major modules
Dashboard for quick insights

# Technologies Used

Java (Core + Swing)

MySQL

JDBC

NetBeans / IntelliJ (recommended IDE)

# Project Structure
StadiumManagementSystem/
│
├── src/
│   ├── admin/
│   ├── booking/
│   ├── events/
│   ├── seats/
│   └── staff/
│
├── database/
│   └── stadium_db.sql
│
├── lib/
│   └── mysql-connector.jar
│
└── README.md

# How to Run the Project
1. Clone the Repository
git clone https://github.com/yourusername/StadiumManagementSystem.git
2. Import into IDE
Open using NetBeans, IntelliJ, or Eclipse
Add MySQL connector JAR to the project's classpath
3. Import Database
Open phpMyAdmin or MySQL Workbench

# Create a database:
CREATE DATABASE stadium_db;
Import stadium_db.sql

4. Update Database Credentials
In the database connection file:
String url = "jdbc:mysql://localhost/stadium_db";
String user = "root";
String pass = "your_password";

5. Run the Project
Execute the main file
Login using admin credentials

# Admin Login (Default)
Username: admin
Password: admin123
