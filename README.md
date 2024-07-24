# CodeAlpha_CGPA_Calculator
# Name-Shreya Ratra 
# Company-CodeAlpha 
# Student ID-CA/JL1/20260
# Domain-C++ Programming 
# Duration- 15TH July TO 15TH August 2024
#
#
## Overview of the Project-
# Project- C++ Program that act as a CGPA Calculator
# Objective- The objective of this project is to build a program that act as a CGPA calculator.The user’s input is used to compute the CGPA, which includes information like the number of courses taken and the grades earned in each one. The program also shows each student’s overall course grade. CGPA Calculator calculates a student’s Cumulative Grade Point Average (CGPA) from the given exam results. The program can show the individual grades of each course, calculate total credits and total grade points achieved, determine the GPA for the semester, and based on all the data, it can generate and present the CGPA of the student.
#
# Key Objectives-
# Capture Course Information: Gather the name, credits, and grade for each course.
# Compute GPA: Calculate the GPA for a semester based on the grades and credits of the entered courses.
# Handle Multiple Semesters: Allow the user to input multiple semesters' worth of courses and calculate the GPA for each.
# Compute CGPA: Calculate the overall CGPA by averaging the GPAs of the entered semesters.
# User Interaction: Provide a simple user interface for inputting course information and deciding whether to add more semesters. 
#
# Technologies Used:
# 1. Standard Library Components
# I/O Stream Library (<iostream>):
Used for standard input and output operations.
# Functions: cin (for input), cout (for output).
Vector Library (<vector>):
Provides the vector container, which is a dynamic array.
Used to store collections of Course objects and GPA values.
# String Library (<string>):
Provides the string class for handling text data.
Used to store the names of courses.
# 2. C++ Programming Concepts
# Structures (struct):
A user-defined data type that groups related variables.
struct Course defines a course with name, credits, and grade attributes.
# Vectors:
Dynamic arrays that can change in size.
vector<Course> courses stores a list of Course objects.
vector<double> gpas stores GPA values for each semester.
# Functions:
calculateGPA: Calculates the GPA for a given semester.
calculateCGPA: Calculates the CGPA by averaging the GPAs of multiple semesters.
# Switch Statements:
Used to handle multiple conditions based on course grades (A, B, C, D, F).
Loops:
For Loop: Iterates over the number of courses to gather input and calculate GPA.
While Loop: Repeats the process for additional semesters based on user input.
# 3. Programming Techniques
# Input Handling:
Uses cin to gather user input for the number of courses, course details (name, credits, grade), and whether to add more semesters.
# Dynamic Data Management:
Uses vectors to dynamically manage the list of courses and GPA values, allowing flexibility in the number of courses and semesters.
Conditional Logic:
Validates grades and calculates grade points based on predefined scales.
# 4. Flow Control
# Main Function:
Handles the primary workflow of the program, including user interaction, GPA calculation for each semester, and CGPA computation.
Prompts the user for input and controls the flow of adding more semesters.
#
# Output-

![Screenshot (37)](https://github.com/user-attachments/assets/4b080eb1-cb90-4762-a6df-08f8154cf5f1)

