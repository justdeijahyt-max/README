#  Project Title
Student Grade Tracker

## Student Information
- Course: CNS1001 - Introduction to Programming  
- Students Name and ID # : Joshua Atkinson (2505156), Lavoy Burke (2209205), Alex Daley (2500977), Deijahnae Hudson (2505962)

## Problem Statement and Background
Students often receive multiple assignments and tests across different modules each semester. This makes it difficult to track grades and determine overall performance. Without a proper system, students may lose track of their academic progress or fail to recognize whether they are passing or failing a module.

This project was developed to solve this problem by providing a simple and organized system that allows students to store, manage, and evaluate their grades in one place. The intended users are students who need an efficient way to monitor their academic performance.

## Program Description and Main Features
The Student Grade Tracker is a menu-driven Python program that allows users to manage their academic records.

Main features include:
- Adding modules
- Adding assessments (tests/assignments)
- Viewing module details
- Calculating weighted averages
- Displaying summaries across all modules
- Identifying pending assessments

The program begins execution in the `main()` function and continuously runs in a loop, allowing users to select options from a menu. Based on user input, specific functions are called to perform tasks such as adding data or displaying results.

The program uses structured data storage, where modules are stored in a list, and each module contains a dictionary with assessment details.

## Programming Concepts Used
- Functions: used to add modules and calculate averages, in addition to other reusable program modules.
- Loops: used to handle lists of modules and tests as well as to keep the program operating.
- Conditionals: used to confirm input and give results like pass/fail.
- Lists/Dictionaries: Modules and assessment data are stored here.
- Input Validation: uses custom functions to make sure that users enter correct information.

## How to Run the Program
1. Open your terminal or command prompt  
2. Go to the project folder  
3. Run the program using:
   python project.py  
4. Follow the onscreen menu options  

## Required Libraries
No external libraries are required.

## Sample Inputs and Outputs
Example Input:
Module: CNS1001  
Assessment: Test 1  
Weight: 50  
Score: 80  

Example Output:
Average: 80.0%  
Grade: A  
Status: PASSING  

## Manual Testing / Validation

| Test Case | Input | Expected Output | Actual Output | Result |
|----------|------|----------------|---------------|--------|
| Valid input | Module: CNS1001; Test1, Weight: 50, Score: 80 | Average = 80%, Grade A, PASSING | Average: 80.0%, Grade: A, PASSING | Pass |
| Exceed weight | Weight: 60 when max = 50 | Input rejected | Enter a value between 0.1 and 50.0 | Pass |
| Invalid score | Score: 150 | Input rejected | Enter a value between 0.0 and 100.0 | Pass |
| Empty input | Module name blank | Input rejected | Input cannot be empty | Pass |
| No modules | Select summary without adding module | No modules found | No modules found | Pass |

## Challenges and Lessons Learned

Challenges:
- Running input validation
- Handling structured information

Solutions:
- developed routines for reusable validation
Data was structured using dictionaries and lists

Lessons Learned:
- The significance of modular programming

- Using loops and conditionals effectively

- Creating systems that are easy to use

## AI Assistance Disclosure
- Tool used: ChatGPT, GitHub and PyCharm AI Assistant
- Purpose: Used to assist with Concept explanations and Debugging
  
