# 📚 Online Book Store Database Project (MySQL)

This project is a MySQL database system for an **Online Book Store**.  
It stores information about books, customers, and orders, and includes SQL queries for analysis and practice.

This project is suitable for:
- DBMS mini project
- College lab record
- SQL learning and practice
- GitHub portfolio project

---

## 🗄 Database Details

- Database Name: OnlineBookStore
- Database Type: MySQL
- Tool Used: MySQL Workbench
- Language: SQL

---

## 📂 Tables in the Database

The database includes the following tables:

### 1️⃣ Books
Stores book information.
- Book_ID (Primary Key)  
- Title  
- Author  
- Genre  
- Published_Year  
- Price  
- Stock  

### 2️⃣ Customer
Stores customer information.
- Customer_ID (Primary Key)  
- Name  
- Email  
- Phone  
- City  
- Country  

### 3️⃣ Orders
Stores order details.
- Order_ID (Primary Key)  
- Customer_ID (Foreign Key – Customer)  
- Book_ID (Foreign Key – Books)  
- Order_Date  
- Quantity  
- Total_Amount  

---

## 🚀 How to Run This Project

### Step 1: Open MySQL Workbench
Connect to MySQL Server.

### Step 2: Run the SQL Script
1. Open the `.sql` file from this repository  
2. Execute the script
3. This will:
   - create the database
   - create tables
   - allow inserting data

### Step 3: Import CSV files (if included)
Right-click table → **Table Data Import Wizard** → select CSV file.

---

## 🔍 SQL Queries Included

The project contains:
- Basic SELECT queries  
- Filtering using WHERE  
- Sorting using ORDER BY  
- Aggregate functions (SUM, COUNT, AVG)  
- GROUP BY and HAVING  
- JOIN queries  
- Advanced analytical questions  

Example tasks:
- find most expensive book  
- list books by genre  
- calculate total revenue  
- find customers with multiple orders  
- get remaining stock after orders  

---

## 🎯 Project Objectives

- Understand relational database design  
- Practice SQL queries  
- Work with real-life bookstore case study  
- Learn MySQL Workbench operations  

---

## 🧑‍💻 Author

Online Book Store Database Project  
Created for academic learning purpose.

