# Student Management Database - SQL

This project contains a Student Management Database created using SQL.

## Features
- Create Database
- Create Students Table
- Insert 10 student records
- Perform SQL queries:
  - Show all students
  - Average scores
  - Top performer
  - Count per grade
  - Average by gender
  - MathScore > 80
  - Update student grade

---

## Task 2 – Extended Database with Relationships

In Task 2, the Student Management Database was extended by adding new tables and implementing table relationships.

### New Tables Added
- **Courses Table**
  - CourseID (Primary Key)
  - CourseName

- **Enrollments Table**
  - EnrollmentID (Primary Key)
  - StudentID (Foreign Key)
  - CourseID (Foreign Key)
  - Grade

### Concepts Implemented
- One-to-Many Relationships
- Foreign Key Constraints
- INNER JOIN
- GROUP BY
- Aggregation Functions (AVG, COUNT)
- ORDER BY and TOP

### Queries Performed
- List all students enrolled in each course
- Calculate average grade per course
- Find top 3 students overall
- Count students who failed (Grade < 40)

### Learning Outcome
- Understanding relational database design
- Working with joins and aggregations
- Performing analytical queries on structured data


---

## Task 3 – Advanced SQL Analysis

In Task 3, advanced SQL queries were implemented to analyze student performance across different courses. This task focuses on using JOINs, GROUP BY, HAVING, and subqueries to perform deeper data analysis.

### Concepts Implemented
- INNER JOIN
- GROUP BY
- HAVING
- Subqueries
- Aggregation Functions (MAX, AVG, COUNT)

### Queries Implemented

1. **Top student per course**
   - Identified the student with the highest grade in each course.

2. **Pass rate per course**
   - Calculated the percentage of students who scored **40 or above** in each course.

3. **Overall topper**
   - Determined the student with the highest average grade across all courses.

4. **Students enrolled in multiple courses**
   - Identified students who are enrolled in more than one course using GROUP BY and HAVING.

### Learning Outcome
- Practiced advanced SQL queries
- Improved understanding of analytical queries
- Learned to analyze relational data using joins and aggregations


---

## Task 4 – Analytical Reports with SQL

In Task 4, analytical reports were generated using SQL joins, aggregations, and subqueries to simulate real-world data analysis scenarios.

### Reports Implemented

1. **Average Grade by Gender**
   - Compared average grades of male and female students across all enrolled courses.

2. **Pass Rate per Course**
   - Calculated pass percentage for each course using grades greater than or equal to 40.

3. **Top 3 Students Overall**
   - Identified top-performing students based on average grades across all courses.

4. **Students Enrolled in Multiple Courses**
   - Listed students enrolled in more than two courses using GROUP BY and HAVING.

5. **Highest Grade Report**
   - Displayed student details with the highest grade across all courses.

### SQL Concepts Used
- INNER JOIN
- GROUP BY
- HAVING
- Aggregate Functions (AVG, COUNT, MAX)
- CASE Statement
- Subqueries

### Learning Outcome
- Generated analytical reports from relational data
- Improved reporting skills using SQL
- Practiced business-style SQL queries
