# 🏫 Escola Técnica - Relational Database

A relational database project designed to manage a technical school system. This project demonstrates database design, table relationships, and SQL querying capabilities using **MySQL / MariaDB**.

---

## Database Schema & Tables

The database consists of three main normalized tables:

1. **`alunos` (Students):** Stores personal information for each student (ID, name, email, birth date, phone).
2. **`cursos` (Courses):** Contains course catalog details, including workload (carga horária) and price.
3. **`matriculas` (Enrollments):** An associative table handling the many-to-many relationship between students and courses, including enrollment dates and status tracking.

---

## 🛠️ Technologies Used
* **Database Management System:** MySQL / MariaDB
* **Environment:** phpMyAdmin / Localhost
* **Language:** SQL

---

## 🚀 How to Import / Run

1. Clone or download this repository.
2. Open your local database manager (such as **phpMyAdmin**, **MySQL Workbench**, or DBeaver).
3. Create a new database named `escola_tecnica`.
4. Import the `escola_tecnica.sql` file into your newly created database.
5. Query the tables to explore the structure and sample data!

---

## 📂 Project Structure
```text
├── escola_tecnica.sql    # Complete SQL dump containing schema and sample data
└── README.md             # Project documentation
