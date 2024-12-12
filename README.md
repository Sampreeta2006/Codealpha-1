Name:v.sampreeta
company:code alpha 
ID:CA/N1/5703
Domain:java programming 
Duration: 15.11.2024 - 15.12.2024
Task 1: student Grade Tracker 
overview of the project :
Overview of the Student Grades Project

Purpose

This project is designed to manage and analyze student grades. It allows a user to input grades for multiple students, validates the inputs, and provides a summary of the data, including the number of students, the average grade, the highest grade, and the lowest grade.

Features

1. Grade Input and Validation

Users can input student grades one at a time.

Input terminates when the user enters -1.

Validates that the grades are between 0 and 100. If invalid, prompts the user to re-enter the grade.



2. Error Handling

Handles non-numeric inputs gracefully by catching exceptions and prompting the user to enter a valid grade.



3. Data Storage

Uses an ArrayList to dynamically store all valid grades entered by the user.



4. Grade Calculations

Average Grade: Computes the average of all entered grades.

Highest Grade: Identifies the highest grade from the list.

Lowest Grade: Identifies the lowest grade from the list.



5. Summary Output

Displays the total number of grades entered.

Displays the average, highest, and lowest grades in a clean summary format.



6. Program Termination

Ends gracefully when the user inputs -1, ensuring resources like the scanner are properly closed.




