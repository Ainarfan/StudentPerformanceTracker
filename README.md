# Student Performance Tracker

## 📘 Project Overview
The **Student Performance Tracker** is a Python-based application designed to help teachers manage and track student scores across various subjects. It calculates individual student averages, determines pass/fail status, and provides a report of overall class performance. The project is structured into three main sections using Object-Oriented Programming (OOP):

1. **Student Class**
2. **PerformanceTracker Class**
3. **Main Program**

## 🛠 Features
- **Student Class**:
  - Manages individual student data (name and scores).
  - Calculates the average score.
  - Checks if the student is passing based on a threshold score (e.g., 40).
- **PerformanceTracker Class**:
  - Maintains a dictionary of students.
  - Adds new students to the tracker.
  - Calculates the overall class average.
  - Displays performance summaries for all students.
- **Main Program**:
  - Handles user input for student names and scores.
  - Manages input validation and error handling.
  - Displays the final report with individual and class performance statistics.

## 🗂️ Project Structure
The project is organized into three sections:

1. **Student Class**:
   - Defines a student with attributes (`name` and `scores`).
   - Methods:
     - `calculate_average()`: Computes the average of the student's scores.
     - `is_passing()`: Checks if the student has passed all subjects based on the threshold.

2. **PerformanceTracker Class**:
   - Manages a collection of student objects using a dictionary.
   - Methods:
     - `add_student()`: Adds a student and their scores to the tracker.
     - `calculate_class_average()`: Calculates the average score across all students.
     - `display_student_performance()`: Prints each student's average score and pass/fail status.

3. **Main Program**:
   - Prompts the teacher to enter student names and their scores for Math, Science, and English.
   - Uses error handling to validate input (handles non-numeric and out-of-range scores).
   - Generates a summary report of student performance and the class average.

## 🚀 How to Run (Google Colab)
To run the project in Google Colab, follow these steps:

1. **Open Google Colab**:
   - Visit [Google Colab](https://colab.research.google.com/).
   
2. **Create a New Notebook**:
   - Click **"New Notebook"** or go to **File** > **New Notebook**.

3. **Copy the Code**:
   - Copy and paste the Python code for each section:
     - **Section 1**: Code for the **Student Class**.
     - **Section 2**: Code for the **PerformanceTracker Class**.
     - **Section 3**: Code for the **Main Program**.

4. **Run the Notebook**:
   - Execute each section in order:
     - Run the code cell for the **Student Class**.
     - Run the code cell for the **PerformanceTracker Class**.
     - Run the code cell for the **Main Program**.

5. **Input Student Data**:
   - Enter student names and their scores when prompted. Type `"done"` when you finish adding all students.

6. **View the Report**:
   - The program will display a summary report of each student's performance and the overall class average.
