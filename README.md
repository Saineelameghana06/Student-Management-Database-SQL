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
