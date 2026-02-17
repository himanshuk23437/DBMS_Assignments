# DBMS Lab – Assignment 03  
## Data Collection and Data Insertion in College Database

---

## 📘 About the Assignment

This assignment focuses on collecting real-world academic data and inserting it into a relational database using SQL.

The objective is to understand how real institutional data is structured and maintained inside a database while ensuring:

- Proper use of primary keys  
- Foreign key constraint satisfaction  
- Data consistency  
- Referential integrity  

The database schema used in this assignment was created in **Lab–2 (ER Diagram and Table Creation).**

All data corresponds to:

**B.P. Mandal College of Engineering, Madhepura, Bihar**

Only authentic sources were used for data collection, such as:

- Official college website  
- Department webpages  
- Academic syllabus  
- Class timetable  
- Academic notices  

No imaginary or randomly generated academic data has been used.

---

## 🗂 Database Tables Used

The following tables were populated:

1. Department  
2. Faculty  
3. Course  
4. Student  
5. Enrollment  

---

## 📂 File Structure

```
Assignment_03/
│
├── Assignment_03_Solution.sql   # Contains all INSERT queries
├── Question_03.pdf              # Original assignment question
├── Department_Cshot.png         # Screenshot of Department table output
├── Faculty_Cshot.png            # Screenshot of Faculty table output
├── Course_Cshot.png             # Screenshot of Course table output
├── Student_Cshot.png            # Screenshot of Student table output
├── Enrollment_Cshot.png         # Screenshot of Enrollment table output
└── README.md                    # Documentation file
```

---

## 🛠 How to Execute the SQL Script

### Step 1: Connect to the Database

Open SQL*Plus or Oracle SQL Developer and connect to your schema:

```sql
CONNECT username/password;
```

---

### Step 2: Ensure Tables Already Exist

Make sure the tables created in Lab–2 are already present.

Verify using:

```sql
SELECT table_name FROM user_tables;
```

---

### Step 3: Execute the SQL File

Run the SQL script:

```sql
@Assignment_03_Solution.sql
```

Alternatively, copy and execute the INSERT queries manually.

---

### Step 4: Verify Data Insertion

Execute:

```sql
SELECT * FROM Department;
SELECT * FROM Faculty;
SELECT * FROM Course;
SELECT * FROM Student;
SELECT * FROM Enrollment;
```

Screenshots of successful execution are included in this repository.

---

## 📊 Requirements Followed

- Minimum 10 records inserted in Student, Course, and Enrollment tables  
- No primary key duplication  
- All foreign key constraints satisfied  
- Data consistency maintained  

---

## ⚠ Assumptions Made

1. Department ID, Faculty ID, Course ID, and Student ID are self-defined but unique.
2. If exact office block details were unavailable, placeholder values like "Block A" or "Block B" were used.
3. Credits were assigned based on syllabus structure where available.
4. Student contact numbers use dummy format (e.g., 9XXXXXXXXX) to maintain privacy.
5. Grades in the Enrollment table (A, B+, etc.) are assumed for representation.

---

## 📚 Data Sources

Data has been collected from:

- Official website of B.P. Mandal College of Engineering
- Department faculty lists
- Academic syllabus and timetable
- Academic notices

---

## ✅ Conclusion

This assignment demonstrates practical data collection, structured SQL insertion, and maintenance of relational integrity within a real-world college database model.

---

**Submitted by:**  
Himanshu Kumar  
B.Tech (CSE)  
DBMS Lab – Assignment 03
