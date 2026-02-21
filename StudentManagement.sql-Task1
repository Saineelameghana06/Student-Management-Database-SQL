/* ============================================
   SQL Data Analysis Internship - Task 1
   Student Management Database
   ============================================ */

-- 1) Create Database
CREATE DATABASE StudentManagement;
GO

-- 2) Use Database
USE StudentManagement;
GO

-- 3) Create Students Table
CREATE TABLE Students (
    StudentID INT PRIMARY KEY IDENTITY(1,1),
    Name VARCHAR(50),
    Gender CHAR(1),
    Age INT,
    Grade VARCHAR(2),
    MathScore INT,
    ScienceScore INT,
    EnglishScore INT
);
GO

-- 4) Insert At Least 10 Records
INSERT INTO Students (Name, Gender, Age, Grade, MathScore, ScienceScore, EnglishScore)
VALUES
('Meghana','F',22,'A',95,90,88),
('Ravi','M',21,'B',78,82,80),
('Anjali','F',20,'A',85,88,92),
('Suresh','M',23,'C',65,70,68),
('Divya','F',22,'B',80,79,85),
('Kiran','M',21,'A',92,95,90),
('Pooja','F',20,'C',60,62,58),
('Arjun','M',22,'B',83,76,79),
('Neha','F',21,'A',88,91,94),
('Rahul','M',23,'C',72,68,70);
GO


/* ============================================
   5) SQL Queries to Perform
   ============================================ */

-- Q1: Show all student details
SELECT * FROM Students;
GO

-- Q2: Average score in each subject
SELECT
    AVG(MathScore) AS AvgMath,
    AVG(ScienceScore) AS AvgScience,
    AVG(EnglishScore) AS AvgEnglish
FROM Students;
GO

-- Q3: Top performer (highest total score)
SELECT TOP 1
    StudentID,
    Name,
    Gender,
    Age,
    Grade,
    MathScore,
    ScienceScore,
    EnglishScore,
    (MathScore + ScienceScore + EnglishScore) AS TotalScore
FROM Students
ORDER BY TotalScore DESC;
GO

-- Q4: Count students per grade
SELECT
    Grade,
    COUNT(*) AS TotalStudents
FROM Students
GROUP BY Grade;
GO

-- Q5: Average score by gender
SELECT
    Gender,
    AVG(MathScore) AS AvgMath,
    AVG(ScienceScore) AS AvgScience,
    AVG(EnglishScore) AS AvgEnglish
FROM Students
GROUP BY Gender;
GO

-- Q6: Students with MathScore > 80
SELECT *
FROM Students
WHERE MathScore > 80;
GO

-- Q7: Update a student's grade (Example: StudentID = 2 -> Grade = 'A')
UPDATE Students
SET Grade = 'A'
WHERE StudentID = 2;
GO

-- Verify update
SELECT * FROM Students WHERE StudentID = 2;
GO
