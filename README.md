# CodeAlpha_project_Studentgradetracker

Name: sabinaya mahapatra

Company: CODE ALPHA

ID: CA/MA1/4435

Domain: Java Programming

Duration: MAY to JUNE,2025

Overview of the Project

Project: Student Grade Tracker

Objective: To develop a console-based Java application that allows users to input student names and marks, calculate grades based on the marks, and generate a summary report of student performance.

Key Activities
Student Data Input: Collect student names and marks from the user.
Grade Calculation: Convert numerical marks into letter grades (A, B, C, D, E, F).
Report Generation: Display a summary report including individual student details, average marks, highest marks, and lowest marks with their corresponding grades.
Input Validation: Ensure that user input for marks and the number of students is valid.
Technologies Used
Java: The programming language used for development.
ArrayList: Used for storing student data dynamically.
Scanner: Used for reading user input from the console.

Program Structure
Classes
Student:

name (String): Student's name.
marks (double): Student's marks.
grade (String): Student's grade.
Constructor to initialize Student objects.
toString() method to provide a string representation of the student's data.
GradeUtils:

convertMarksToGrade(double marks) (static): Method to convert marks to a letter grade.
StudentGradeTracker:

main(String[] args): Main method to execute the program.
collectStudentData(): Method to collect student information.
showStudentReport(ArrayList<Student> students): Method to generate and display the student report.
getValidMarksInput(String prompt): Method to get valid marks input from the user.
getPositiveIntegerInput(String prompt): Method to get a positive integer input from the user.
askToContinue(): Method to ask the user if they want to enter more student data.
Compilation and Execution
Prerequisites
Java Development Kit (JDK) installed.
Compilation
Save the code as StudentGradeTracker.java.

Open a command prompt or terminal.

Compile the code:

javac StudentGradeTracker.java

Execution

Execute the compiled code:
java StudentGradeTracker
Usage
The program will prompt you to enter the number of students.
For each student, you will be prompted to enter their name and marks.
The program will then display a report summarizing the student data.
You will be asked if you want to enter data for more students.

Future WORK
1 Data Persistence: Implement functionality to save and load student data from files (e.g., CSV, JSON) or a database.
2 Graphical User Interface (GUI): Develop a graphical interface using libraries like Swing or JavaFX for a more interactive experience.
3 More Detailed Reporting: Add features like generating grade distributions, individual student progress over time, or exporting reports in different formats (e.g., PDF).
4 User Authentication: Implement user accounts and login functionality for multiple users.
5 Error Handling Enhancements: Add more robust error handling and user feedback for invalid inputs or unexpected situations.
6 Configuration Options: Allow users to customize the grading scale or other application settings.
7 Search and Sorting: Implement features to search for specific students and sort the report based on different criteria (e.g., name, marks, grade).
