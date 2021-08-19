# student-report-card
Student report card system project in C++ is a simple console application built without the use of graphics. In this project, users can perform typical report card related functions like adding a new student record and displaying, modifying, editing and deleting it. File handling has been effectively used to perform all these. This project will teach you how to use file handling in C++, add, read, display, search, modify and delete record from file.
File handling has been used for the effective implementation of all the typical features of this project. The key features of Student Report Card System are:

1. Create student report card record: This feature creates a new student record containing his marks. For this the information to be provided are the name and roll no. of the student, and the marks obtained by him/her in 5 subjects – Physics, Chemistry, Maths, English and Computer Science.


 
2. Read all students report card record: The void display_all() function in this student report card system project in C++ has been used for this feature. It basically shows the progress report of all the students added in file. This feature displays the roll no. and name of all the students, the marks obtained by them in 5 subjects – Physics, Chemistry, Maths, English and Computer Science, along with the percentage and grade of each student.

3. Read specific student’s report card record: This feature is same as the one explained above, except it shows the progress report and relevant data related to a particular student.

4. Display all students’ grade report: This feature enlists all the students’ record saved in file. The grade report is displayed in a tabular form with roll no. and name of the students, marks achieved in the five subjects, and the grade and percentage obtained by them.

5. Modify student’s report card record: In student report card system project in C++, this feature is used to edit the report card record of a particular student. For this, the name and roll no. of the student is sought. Upon successful modification, the program displays the message “Record Updated”. If no record of student is found in file, it displays the message “Record not found”.

6. Delete student record: This feature deletes the report card record of a particular student; it first of all asks for the name and roll no. of the student whose record is to be deleted.

Header Files Used:

Student report card system is a very simple project that runs with just five header files. The conio.h header file is required to compile the source code in Turbo C++; it is not required in Code::Blocks . Also, in order to make the project simple and easy to understand and analyze, graphics has not been used in this project. Here, are the header files required for this project:

#include<conio.h>
#include<stdio.h>
#include<process.h>
#include<fstream.h>
#include<iomanip.h>
