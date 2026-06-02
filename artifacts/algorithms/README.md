# Course Planner Application

## Overview

The Course Planner application is a C++ program developed in **CS-300 Data Structures and Algorithms**. The program loads course information from a file, stores course data, allows users to search for specific courses, and prints course information in alphanumeric order.

This artifact is being used for the **Algorithms and Data Structures enhancement category** in the **CS-499 Computer Science Capstone**.

## Features

* Load course data from a CSV file
* Store course information using data structures
* Search for courses by course number
* Display prerequisite information
* Print course lists in alphanumeric order
* Analyze efficiency and tradeoffs between data structures

## Algorithms and Data Structures

This project focuses on:

* Vectors
* Searching algorithms
* Sorting algorithms
* Runtime complexity analysis
* Binary Search Trees (BST)
* Hash Tables
* Data structure performance tradeoffs

The original implementation stores and retrieves course data using vectors while evaluating alternative structures for performance and efficiency.

## Files Included

* `CoursePlanner.cpp` – Main application source code
* `CoursePlanner.sln` – Visual Studio solution file
* `CoursePlanner.vcxproj` – Visual Studio project file
* `CS 300 ABCU_Advising_Program_Input.csv` – Course input data file

## Running the Project

### Requirements

* Visual Studio 2022 Community (recommended)
* Desktop Development with C++ workload installed

### Running the Program

1. Open `CoursePlanner.sln` in Visual Studio.
2. Build the solution.
3. Run the application using:

```text
Ctrl + F5
```

4. Use the menu to:

* Load course data
* Print course lists
* Search for a specific course

## Planned Enhancements

As part of the CS-499 capstone enhancement, this artifact will be expanded to:

* Improve searching and sorting efficiency
* Implement and compare hash tables and binary search trees
* Benchmark runtime performance between structures
* Improve prerequisite lookup performance
* Analyze scalability and algorithmic tradeoffs

## Notes

The program uses the included CSV input file to load course information. Ensure the CSV file remains in the project directory when running the application.

