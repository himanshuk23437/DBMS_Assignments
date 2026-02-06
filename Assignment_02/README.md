# DB Lab 2 – College Database Design & Implementation

## 📘 About
This assignment focuses on the full lifecycle of database design, from conceptual modeling to SQL implementation. It involves creating an Entity-Relationship (ER) diagram for a college system and converting that design into a relational schema with appropriate constraints.

## 📂 File Structure
- **ER_Diagram.png/pdf**: Visual representation of the entities (Student, Faculty, Course, Department, Enrollment) and their relationships.
- **Assignment_02_Solution.sql**: SQL script containing the `CREATE TABLE` statements, primary keys, and foreign key constraints.
- **Question_02.pdf**: The original assignment requirements and business rules.

## 🏛️ Database Schema Overview
The system is built around five core entities:
* **[span_0](start_span)Department**: The central academic unit[span_0](end_span).
* **[span_1](start_span)Course**: Subjects offered by departments and taught by faculty[span_1](end_span).
* **[span_2](start_span)Student**: Enrolled individuals belonging to a specific department[span_2](end_span).
* **[span_3](start_span)Faculty**: Academic staff teaching one or more courses[span_3](end_span).
* **[span_4](start_span)Enrollment**: A bridge table managing the Many-to-Many relationship between Students and Courses, including semester and grade data[span_4](end_span).

## ▶ How to Execute
1. Open **Oracle SQL Developer**.
2. Connect to your database instance.
3. Open `Assignment_02_Solution.sql`.
4. Execute the script to generate the tables and establish relational integrity through foreign keys.

## 📝 Key Design Constraints
* **[span_5](start_span)[span_6](start_span)[span_7](start_span)Cardinality**: Handled 1:M relationships (e.g., Department to Student) and M:N relationships (Student to Course via Enrollment)[span_5](end_span)[span_6](end_span)[span_7](end_span).
* **[span_8](start_span)Data Integrity**: All tables include Primary Keys (e.g., `StudentID`, `CourseID`) and Foreign Keys to maintain referential integrity[span_8](end_span).
* **[span_9](start_span)Tools Used**: The ER Diagram was created using professional software (draw.io/diagrams.net) as per the requirements[span_9](end_span).
