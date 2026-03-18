# Examination System Database

A fully functional examination system database built with SQL Server and T-SQL as a team project during ITI's 9-month Professional Web Development & BI program.

## 📋 Overview
A complete database system that manages students, instructors, courses, tracks, exams, questions, and answers — with automated exam generation, correction, and reporting.

## 🗄️ Database Structure
- 17 relational tables with full ERD
- Covers: Branches, Tracks, Instructors, Courses, Topics, Students, Exams, Questions, Choices, and Answers

## ⚙️ Stored Procedures (112 Total)
| Category | Count |
|---|---|
| Main Entities CRUD (9 tables × 4) | 36 |
| Many-to-Many Relations CRUD | 58 |
| Exam Generation & Correction | 5 |
| Report Stored Procedures | 6 |
| Extra business logic helpers | 7 |

## 🚀 Key Features
- **Random Exam Generation** — selects MCQ and True/False questions randomly per course
- **Auto Exam Correction** — validates student answers and calculates scores and percentages
- **Model Answer Retrieval** — returns correct answers for any exam
- **Student Answer Tracking** — with and without correct choice info
- **6 SSRS Reports** built with Microsoft Report Builder:
  1. Students by Track
  2. Student grades across all courses
  3. Instructor courses and student count
  4. Course topics
  5. Exam questions with choices
  6. Student exam answers

## 🛠️ Tech Stack
- SQL Server
- T-SQL
- SSRS (SQL Server Reporting Services)
- Microsoft Report Builder

## 📁 Repository Structure
```
├── Stored Procedures Code/
│   ├── please_start_with_me.sql        ← Start here for quick testing
│   ├── Main_Entities_Stored_Procedures.sql
│   ├── Many_To_Many_Entities_Stored_Procedures.sql
│   ├── Exam_Generation_Answers_Correction_Stored_Procedures.sql
│   └── Reports_Stored_Procedures.sql
├── System ERD/
├── DB Documentation/
├── Reports PDF/
├── DB Backup/
└── IMPORTANT_NOTE.txt
```

## ▶️ Getting Started
1. Restore the `.bak` file from `DB Backup/` in SQL Server Management Studio
2. Run `please_start_with_me.sql` to populate sample data (5 exams, 21 students, 210 answer rows)
3. Run any stored procedure to test the system

## 👥 Team
Built by a team of 5 — ITI Professional Web Development & BI Program, 2025
