# Hospital Management System

A simple console-based Hospital Management System built using Java, JDBC, and MySQL.
This project allows hospitals to manage patients, doctors, and appointments efficiently.

🚀 Features

- ➕ Add new patients with details stored in MySQL database

- ‍⚕️ View doctors available in the hospital

- 📋 View patient records

- 📅 Book appointments with validation (doctor availability check)

- ❌ Prevents duplicate appointments for the same doctor on the same date

🛠️ Tech Stack

- Programming Language: Java

- Database: MySQL

- JDBC Driver: MySQL Connector (com.mysql.cj.jdbc.Driver)

IDE: IntelliJ IDEA / Eclipse (any Java IDE)

## 📂 Project Structure

HospitalManagementSystem/
│── HospitalManagementSystem.java # Main driver class
│── Patients.java # Handles patient-related operations
│── Doctor.java # Handles doctor-related operations
│── Appointments (table in MySQL) # Stores appointments