# 🚦 Traffic Management System using SQL

## 📌 Project Overview
The **Traffic Management System** is a database-driven project developed using **MySQL** to automate traffic violation tracking, fine calculation, and payment management.  
It demonstrates both **core and advanced SQL concepts** through a real-world use case.

---

## 🎯 Objectives
- Manage users and their vehicles efficiently
- Record and track traffic violations
- Automatically calculate fines based on violation type
- Update payment status in real time
- Generate analytical and reporting queries
- Implement secure, role-based access control

---

## 🗄️ Database Details
**Database Name:** `traffic`

### Tables Used
- `users` – Stores driver information
- `vehicles` – Stores vehicle ownership details
- `violations` – Records traffic violations and fines
- `payments` – Stores fine payment transactions
- `fine` – Tracks fine status per vehicle

---

## 🧩 Key Features
- ✅ Automatic fine calculation using SQL Triggers  
- ✅ Real-time status update after payment  
- ✅ Stored Procedure for pending fines  
- ✅ Views for simplified data retrieval  
- ✅ Window functions for ranking and analytics  
- ✅ Data integrity using constraints  
- ✅ Secure access using GRANT and REVOKE  

---

## ⚙️ SQL Concepts Used
- DDL & DML (`CREATE`, `INSERT`, `UPDATE`, `DELETE`)
- Constraints (`PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, `CHECK`, `DEFAULT`)
- Joins & Subqueries
- Aggregate Functions (`SUM`, `MAX`, `COUNT`)
- Date & String Functions
- Conditional Logic (`CASE`, `IFNULL`, `COALESCE`)
- Views & Indexes
- Triggers (BEFORE INSERT, AFTER INSERT)
- Stored Procedures
- Window Functions (`RANK`, `ROW_NUMBER`)
- Database Security (`GRANT`, `REVOKE`)

---

## 🔁 Triggers Used
### 1. Automatic Fine Calculation
- Sets fine amount based on violation type  
  (Signal Jump, Over Speed, No Helmet, etc.)

### 2. Automatic Payment Status Update
- Updates `paid_amount`
- Changes status to **Completed** when full fine is paid

---

## 📂 Stored Procedure
**Procedure Name:** `view_pending_fines`  
- Displays all pending fines  
- Joins users, vehicles, and violations  
- Improves query reusability

---

## 📊 Sample Reports
- Total fine collected per day
- Users with multiple violations
- Vehicles with pending fines
- Fine category (High / Low)
- Rank of payments by amount

---

## 🔐 Security Implementation
- Created database users
- Assigned role-based privileges
- Restricted unauthorized DELETE operations

---

## 🚀 Future Enhancements
- Integration with traffic cameras and sensors
- Online payment gateway support
- Mobile and web application interface
- AI-based violation detection
- Advanced dashboards using Power BI or Tableau

---

## 🛠️ Technologies Used
- MySQL
- SQL

---

## 📚 Learning Outcome
This project provided hands-on experience in:
- Relational database design
- SQL automation using triggers
- Writing optimized and analytical queries
- Implementing secure database systems

---


## 📄 License
This project is for academic and learning purposes.
