Student Grade Sheet Management System

Project Description
•The Student Grade Sheet Management
System is a console-based C programming project designed to manage student academic records efficiently.
•It allows users to store student details, calculate total marks, percentage, and grades automatically, and retrieve records using search options.
•The system uses file handling to ensure permanent storage of student data and provides a menu-driven interface for easy access.

Features
•Add student details (ID, Name, Branch, Marks)
Automatic calculation of:
•Total Marks
•Percentage
•Grade

Store student records permanently using file handling
Search student details by:
•Student ID
•Student Name
•Branch

Display formatted STUDENT GRADE SHEET
Menu-driven and user-friendly system

Technologies Used
Programming Language: C

Concepts Used:
•Structures
•Arrays
•Loops
•Conditional Statements
•Functions
•File Handling

How to Run the Project
(All Operating Systems)
Step 1: Open Terminal / Command Prompt

Windows: Open Command Prompt
Linux / macOS: Open Terminal

Step 2: Navigate to Project Folder
cd path_to_project_folder

Step 3: Compile the Program
gcc student_grade_sheet.c -o student_grade_sheet

Step 4: Run the Program
./student_grade_sheet
(or student_grade_sheet.exe on Windows)

Files in the Project
•student_grade_sheet.c → Main source code
•students.txt → Stores student records permanently

Notes
•Student data is stored in binary file format using file handling
•Data remains saved even after program termination
•Searching is performed by reading records from the file
•Program supports multiple students dynamically


•Sample Output
============================================================
              STUDENT GRADE SHEET
============================================================
Name       : M. Shanmukheswar
ID         : 4353
Branch     : AI

Subject 1  : 100
Subject 2  : 98
Subject 3  : 95
Subject 4  : 97
Subject 5  : 99

Total Marks : 489 / 500
Percentage  : 97.80 %
Grade       : A
=============================================================


•Team Members
25A31A4353 – Medicharla Shanmukheswar(TEAM LEAD)
25A31A4305 – D Lasya Bharathi
25A31A4356 – N G Jaya Surya Kumar
25A31A4314 – Katta Vaishnavi
25A31A4310 – G V Venkata Jaisree


Conclusion
•The Student Grade Sheet Management System automates student result management using C programming and file handling.
•It reduces manual effort, improves accuracy, and allows quick access to student records.
•This project is ideal for beginners and can be extended further with GUI or database integration.
