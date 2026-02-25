# ✈️ Flight Management System (SQL Project)

## 📌 Project Overview
This project is a relational **Flight Management System** built using **MySQL**.  
It simulates how airlines manage airports, flights, passengers, and ticket bookings while generating useful business insights through SQL queries.

---

## 🗂️ Database Schema

The database consists of 5 main tables:

- **Airports**
- **Airlines**
- **Flights**
- **Passengers**
- **Tickets**

### 🔗 Relationships
- Flights reference Airports (Origin & Destination)
- Flights reference Airlines
- Tickets reference Passengers and Flights
- Implemented using **Primary Keys** and **Foreign Keys**

---

## 🛠️ Technologies Used
- MySQL
- SQL (Joins, CTEs, Window Functions, Aggregations)

---

## 📊 Key SQL Queries Implemented

✔️ Find the busiest airport by number of departures  
✔️ Calculate total tickets sold per airline  
✔️ List flights operated by a specific airline (e.g., IndiGo)  
✔️ Rank top airline per airport using `RANK()` window function  
✔️ Categorize flights as Short / Medium / Long using `TIMESTAMPDIFF()`  
✔️ Analyze passenger travel history (first flight, last flight, total flights)

---

## 💡 Concepts Practiced

- INNER JOIN
- GROUP BY & ORDER BY
- Aggregate Functions
- CASE Statements
- Common Table Expressions (CTE)
- Window Functions
- Database Design & Normalization
- Foreign Key Constraints

---

## 📈 Learning Outcome

This project helped me:
- Strengthen SQL query writing skills
- Understand relational database design
- Apply analytical thinking to real-world business problems
- Work with structured datasets

---

## 🚀 Future Improvements

- Add stored procedures
- Implement indexing for performance optimization
- Build a frontend interface
- Connect with a backend application (Java / Python)

---

## 👨‍💻 Author
Pavan  
B.Tech Computer Science Engineering  
Passionate about Backend Development & Data Analytics  

---

⭐ If you found this project useful, feel free to star the repository!
