# Vityarthi_Python-Project 

##Student Marks Record Management System

#Project Overview

The Student Marks Record Management System is a Python-based project developed to store and manage student academic records efficiently. The system stores important student details such as Roll Number, Name, and Marks using Python dictionaries and file handling.

The project provides a simple menu-driven interface that allows the user to insert, display, search, update, and delete student records. The records are stored permanently in a binary file using Python's pickle module.

This project demonstrates the practical use of Python functions, dictionaries, file handling, loops, conditional statements, and the pickle module.

#Features

Add new student records.

Display all stored student records.

Search for a student using Roll Number.

Update the marks of an existing student.

Delete a student record using Roll Number.

Store records permanently in a binary file.

Use a simple menu-driven interface.

Handle multiple student records.

Easy to use and understand.


# Technologies/Tools Used

Programming Language: Python 3

Modules: pickle, os

Data Structure: Dictionary

File: student.dat

File Type: Binary file

IDE/Editor: VS Code / IDLE / PyCharm / any Python-supported editor

#Project Working

The project uses a dictionary to store the details of each student:

Roll Number

Name

Marks


The pickle module is used to store these dictionaries in the student.dat file.

The program provides the following operations:

1. Insert Record – Adds a new student's details.


2. Display Records – Shows all saved student records.


3. Search Record – Finds a student using their Roll Number.


4. Update Record – Changes the marks of an existing student.


5. Delete Record – Removes a student's record.


6. Exit – Closes the program.


# Steps to Install and Run the Project

Step 1: Install Python

Install Python 3.x on your computer.

Step 2: Create the Project Folder

Create a folder named:

Student Marks Record Management System

Step 3: Save the Program

Save the Python source code inside the folder, for example:

student_record.py

Step 4: Open the Terminal

Open Command Prompt or Terminal in the project folder.

Step 5: Run the Program

Use the following command:

python student_record.py

Step 6: Select an Operation

The program will display a menu. Enter the number corresponding to the operation you want to perform.

#Instructions for Testing

The following test cases can be performed to verify the project:

Test Case 1 – Insert Record

Select the Insert Record option and enter:

Roll Number

Name

Marks


Check whether the record is successfully stored.

Test Case 2 – Display Records

Select Display Records and verify that all stored student details are displayed correctly.

Test Case 3 – Search Record

Enter an existing Roll Number and verify that the correct student's details are displayed.

Test Case 4 – Update Marks

Enter an existing Roll Number and provide the new marks. Verify that the marks are updated successfully.

Test Case 5 – Delete Record

Enter an existing Roll Number and verify that the corresponding student record is deleted.

Test Case 6 – Record Not Found

Enter a Roll Number that does not exist and verify that the program displays an appropriate message such as "Record Not Found".
