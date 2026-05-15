# Smart Student Marks Organizer (SSMO)
### Algorithms Lab Project – Binary Brains

---

## 1. Executive Summary
The **Smart Student Marks Organizer (SSMO)** is a console-based student record management application developed in **ANSI C** as part of the **CSE214: Algorithms Lab** course at **Daffodil International University (DIU)**.

This system demonstrates the practical implementation of core algorithmic and data-structure concepts—including **singly linked lists, Quick Sort, Binary Search, dynamic memory management, and file persistence**—to solve real-world academic record management problems efficiently.

The project provides a complete academic management workflow with functionalities such as:
- Student record insertion with validation
- Quick Sort-based ranking system
- Binary Search-based student lookup
- Section-wise student exploration
- Course average bar graph generation
- Persistent storage using file handling

---

## 2. Group Information
**Group Name:** Binary Brains

**Leader:**  
- Sk. Azmain Zunaeid (251-15-222)

**Members:**  
1. Md. Maruf Mia (251-15-042)  
2. Syeda Zawada Farah (251-15-223)  
3. Tahmid Ibne Mofazzol (251-15-548)  
4. Md. Delower Sarker (251-15-457)

---

## 3. Academic Information
- **Program:** Bachelor of Science in Computer Science and Engineering (CSE)  
- **Course Code:** CSE214  
- **Course Title:** Algorithms Lab  
- **Semester:** Spring 2026  
- **Section:** 68_A1  
- **Course Instructor:** *Ms. Nishat Sadaf Lira (Lecturer)*  
- **University:** Daffodil International University (DIU)

---

## 4. System Description

### 4.1 Student Record Management Module (Singly Linked List)
- Stores student records dynamically using a singly linked list.  
- Maintains sorted insertion based on student ID.  
- Stores:
  - Student ID
  - Student Name
  - Section
  - Five Course Marks
  - Total Marks
- Supports:
  - Add Student
  - Remove Student
  - Explore Students by Section
  - View All Ranked Students
- Uses persistent storage through **cse_students_db.txt**.

### 4.2 Ranking & Search Module (Quick Sort + Binary Search)
- Implements **Quick Sort** to rank students based on total marks in descending order.  
- Displays:
  - Top 3 Students (Hall of Fame)
  - Full Student Ranking
- Implements **Binary Search** for efficient student lookup by ID.  
- Converts linked list into array of pointers for optimized searching and sorting operations.

### 4.3 Analysis & Visualization Module
- Generates section-wise course average analysis.  
- Displays visual bar graph representation using console graphics (`#`).  
- Helps analyze academic performance trends across sections.

### 4.4 User Interface Module
- Menu-driven console interface.  
- Strong validation for:
  - Duplicate IDs
  - Invalid names
  - Invalid marks
  - Incorrect input types
- Provides informative prompts and responsive feedback for all operations.

---

## 5. Key Features
- **Persistent Student Database:** Automatic save/load functionality.  
- **Quick Sort Ranking System:** Efficient student ranking by total marks.  
- **Binary Search Student Finder:** Fast ID-based lookup.  
- **Sorted Linked List Insertion:** Maintains organized student records.  
- **Section-Wise Analytics:** Course average analysis with bar graphs.  
- **Robust Input Validation:** Prevents invalid or inconsistent data.  
- **Dynamic Memory Management:** Efficient memory allocation and deallocation.  
- **Modular ANSI C Implementation:** Clean and maintainable project structure.

---

## 6. System Architecture
The architecture consists of:
- **Singly Linked List** for student record storage  
- **Quick Sort Algorithm** for ranking operations  
- **Binary Search Algorithm** for efficient lookup  
- **File I/O Layer** for persistent storage  
- **Console-Based User Interface** for interaction and workflow management  

This architecture ensures modularity, efficiency, scalability, and maintainability.

---

## 7. Technologies and Concepts
| Component | Technology / Concept |
|----------|----------------------|
| Language | ANSI C |
| Data Structures | Singly Linked List |
| Algorithms | Quick Sort, Binary Search |
| Storage | Text File (`cse_students_db.txt`) |
| Concepts | Pointers, Recursion, File Handling, Dynamic Memory Allocation |
| Tools | GCC, Visual Studio Code |
| Platforms | Windows / Linux / macOS |

---

## 8. How to Run

### Step 1 — Compile
gcc SSMO_CSE214_Project_Code_Binary_Brains_68_A1_Spring_2026_DIU.c -o SSMO

### Step 2 — Run
./SSMO

(Windows: SSMO.exe)

---

## 9. Example Workflow

### Add Student Workflow
1. Enter unique student ID.
2. Enter valid student name.
3. Enter section.
4. Input marks for five courses.
5. System calculates total automatically.
6. Student added in sorted order and saved permanently.

### Ranking Workflow
1. Select Top 3 Ranking or View All Ranked Students.
2. System applies Quick Sort.
3. Students displayed based on descending total marks.

### Student Search Workflow
1. Enter student ID.
2. System applies Binary Search.
3. Complete student record displayed instantly.

### Section Analysis Workflow
1. Enter section name.
2. System calculates average marks for each course.
3. Console bar graph generated for visualization.

---

## 10. Project Structure

├── SSMO_CSE214_Project_Code_Binary_Brains_68_A1_Spring_2026_DIU.c  
├── cse_students_db.txt  
├── README.md  
└── Additional (report/presentation files)

---

## 11. Contributors

Developed collaboratively by Binary Brains through structured teamwork, algorithmic analysis, implementation, testing, debugging, documentation, and presentation preparation.

---

## 12. License

MIT License

Copyright (c) 2026 Sk Azmain Zunaeid

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

## 13. Acknowledgements

Special thanks to Ms. Nishat Sadaf Lira, Course Instructor,
for her continuous guidance, valuable feedback, and academic support throughout the project development process.

---
