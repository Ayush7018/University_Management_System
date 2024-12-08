# University_Management_System

The University Management System is a console-based application written in C++ to manage university student records. It allows users to perform operations such as adding, searching, and updating student information, with data persistence achieved through file handling.

<h3>Features</h3>
Add Student

Collects and stores student details: Roll No, Name, Subject, and Address.
Appends data to a text file for persistence.
Search Student

Searches for a student using their Roll No.
Displays the matching record from the file if found.
Update Student

Updates the Address of a student by their Roll No.
Modifies the data in the file while retaining other records.
Exit

Exits the program gracefully.
Technologies Used
Programming Language: C++
Libraries: <iostream>, <fstream>, <windows.h>
File Handling: Data is stored in university.txt located at D:/.
Prerequisites
Windows operating system (uses <windows.h> for Sleep() and system() functions).
A C++ compiler such as GCC or MSVC.
The file university.txt should exist in the D:/ directory (or the code should be modified to create it dynamically).
