# Pharmacy Management System

Pharmacy Management System is a desktop application that helps pharmacies digitalize their workflows.  
The system supports managing products, inventory, customers, suppliers, invoices, and employees — making pharmacy operations more efficient and reliable.

---

## Features

This system provides role-based features for different types of users.

### 👨‍💼 Manager
- Add, edit, delete, and assign roles to employees  
- Manage login accounts and permissions  
- View revenue, cost, and profit statistics by day, month, and year  

### 🛒 Sales Staff
- Create invoices and process payments  
- Search/manage invoices by customer name or invoice ID  
- Manage customer information (name, phone, address)  
- View personal sales statistics  

### 📦 Inventory Manager
- Create purchase receipts from suppliers  
- Manage products (name, code, category, price, stock, origin)  
- Manage suppliers (code, name, phone, address)  
- Manage purchase receipts (ID, date, supplier, total amount)  
- View inventory and purchase statistics  

---

## Technologies Used

- **Frontend**: Java Swing (desktop UI)  
- **Backend**: Java, JDBC  
- **Database**: PostgreSQL  

---

## Installation and Running Guide

Follow these steps to install and run the project locally.

### 1. Clone the repository
```bash
git clone https://github.com/DavidNA-VN/pharmacy.git
cd pharmacy
```

### 2. Setup Database (PostgreSQL)
```sql
CREATE DATABASE oop_database;
\i path/to/oop_database.sql
```

### 3. Setup Project in Eclipse
```text
1. Open Eclipse → File → Import → Existing Project into Workspace
2. Configure DB connection (host, port, dbname, username, password)
3. Add postgresql.jar to Build Path
```

### 4. Run Application
```bash
java Login.java
```

Available roles include:
- Admin  
- Sales Staff  
- Inventory Manager  

---

## Troubleshooting
- **Database connection error** → check that the database exists and credentials are correct  
- **Driver not found** → add `postgresql.jar` into the Eclipse Build Path  
- **Cannot run project** → make sure you start from `Login.java`  

---

## Author
Developed by **DavidNA-VN**
