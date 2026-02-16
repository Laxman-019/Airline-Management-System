# ✈️ Airline Management System

A desktop-based **Airline Management System** developed using **Java (Swing/AWT)** in **Apache NetBeans IDE** with **MySQL Database connectivity using JDBC**.

This project is designed to manage airline operations such as flight management, passenger registration, and ticket booking.

---

## 📌 Project Description

The Airline Management System is a Java GUI-based application that helps manage airline booking operations efficiently. It provides an easy-to-use interface for managing flights, passengers, and ticket reservations.

This project is suitable for:
- DBMS Mini Project
- Java GUI Project
- Final Year Academic Project

---

## 🚀 Features

- 🔐 Admin Login System
- 🛫 Add / View Flight Details
- 👤 Add / View Passenger Details
- 🎫 Book Tickets
- 📄 View Ticket Information
- ❌ Cancel Reservations
- 📊 Simple and User-Friendly GUI

---

## 🛠️ Technologies Used

- **Java (Swing & AWT)** – For GUI development  
- **Apache NetBeans IDE** – Development environment  
- **MySQL** – Database management  
- **JDBC (Java Database Connectivity)** – Database connection  

---

## 🗂️ Project Structure

```
Airline-Management-System/
│
├── Airline Management System/
│   │
│   ├── build/
│   │   └── classes/
│   │
│   ├── nbproject/
│   │
│   ├── src/
│   │   └── airline/
│   │       └── management/
│   │           └── system/
│   │               │
│   │               ├── icons/
│   │               │
│   │               ├── AddCustomer.java
│   │               ├── BoardingPass.java
│   │               ├── BookFlight.java
│   │               ├── Cancel.java
│   │               ├── Conn.java
│   │               ├── FlightInfo.java
│   │               ├── Home.java
│   │               ├── JourneyDetails.java
│   │               └── Login.java
│   │
│   ├── build.xml
│   └── manifest.mf
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/Laxman-019/Airline-Management-System.git
```

### 2️⃣ Open in NetBeans

- Open Apache NetBeans

- Click File → Open Project

- Select the cloned project folder

### 3️⃣ Setup Database

- Install MySQL.

- Create a new database:

- CREATE DATABASE airline;


- Create required tables such as:

- flight

- passenger

- reservation

- ticket

- Update database credentials in your Java connection file:
```
Connection con = DriverManager.getConnection(
    "jdbc:mysql://localhost:3306/airline",
    "username",
    "password"
);
```
### 4️⃣ Run the Project

- Right-click project → Run

- Login and start managing airline operations
