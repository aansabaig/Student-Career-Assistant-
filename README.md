# 🌸 Student Career Assistant

A command-line application built with Python that helps 
students track their academic journey, monitor their 
performance, and receive personalized advice based on 
their progress.

---

## 👥 Team Members
- Aansa Baig
- Aqsa Ibrahim

## 📚 Course
AICT — Artificial Intelligence & Computer Technology

---

## 💡 Project Idea
Most students struggle to keep track of their grades,
attendance and skills in one place. This tool solves 
that problem by giving every student a personal 
academic assistant that remembers their data and 
advises them based on their actual performance.

---

## ✨ Features

### 🔢 Binary Student ID
Every student gets a unique ID converted to binary.
This demonstrates how computers store information
using the binary number system (1s and 0s).
Example: Student ID 101 → Binary: 1100101

### 📊 Grade Tracker
- Add grades for any subject
- View grade history
- Animated progress bar for visual feedback
- Automatic warnings based on performance:
  - Below 50% → Critical warning
  - 50-75% → Encouragement
  - Above 75% → Excellent feedback

### 📅 Attendance Tracker
- Record total classes and attended classes
- Calculates attendance percentage automatically
- Warns when attendance drops below 75%
- Validates that attended cannot exceed total classes

### 💡 Skills Tracker
- Add new skills learned
- View all skills in a list
- Tracks your growth over time

### ♥ Personal Progress Advisor
The advisor analyzes your actual data and gives
personalized advice based on your situation:
- 85%+ average → Outstanding! Confidence boost
- 70-84% average → Great work! Keep pushing
- 50-69% average → Average! Motivational advice
- Below 50% → Needs improvement + how to study tips
Also gives separate advice on attendance and skills!

### 💾 Data Persistence
All data is saved to a JSON file so your records
stay safe even after closing the program.
Nothing resets between sessions!

---

## 🛠️ Technologies Used
- Python 3
- JSON (saving and loading student data)
- OS module (file handling)
- Time module (animated progress bars)
- Random module (personalized tips)

---

## 💻 Concepts Applied
- Binary number system (bin() function)
- File handling (read/write JSON)
- Functions and loops
- Conditional statements
- Lists and dictionaries
- Data persistence
- Command line interface (CLI)

---

## ▶️ How to Run

### Requirements
- Python 3 installed on your computer

### Steps
1. Download or clone the project folder
2. Open CMD (Command Prompt)
3. Navigate to the project folder:
   cd path\to\project
4. Run the program:
   python main.py
5. Enter your name and student ID
6. Use the numbered menu to navigate

---

## 📁 Project Structure

project/
├── main.py            → Main program file
├── student_data.json  → Saved student data (auto created)
└── README.md          → Project documentation

---

## 🖥️ Sample Output

========================================================
            Student Career Assistant
========================================================
Enter your name: Aansa
Enter your student ID: 101

Welcome, Aansa!
Your Binary ID: 1100101

--- MENU ---
1. View Grades
2. Attendance
3. Skills
4. My Progress Summary
5. Quit

---

## 🔍 How Binary ID Works
We use Python's built-in bin() function:

    binary_id = bin(int(student_id))[2:]

- int() converts the ID to a number
- bin() converts it to binary
- [2:] removes the "0b" prefix
- Result: a unique binary identity for each student!

---

## 🌸 Why This Project Stands Out
- Data saves between sessions (most beginner 
  projects reset every time)
- Personalized advice based on real data
- Animated progress bars for visual feedback
- Binary concept integrated meaningfully
- Validates user input to prevent errors
- Complete menu system with sub-menus

---

Made with hard work and lots of debugging! 💪
