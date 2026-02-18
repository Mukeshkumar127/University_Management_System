🎓 University Management System (C++)

A simple University Management System built using C++, demonstrating Object-Oriented Programming (OOP) concepts and file handling. The program allows users to add, search, and update student records stored in a text file.

📌 Features

- Add a student record
- Search a student by Roll Number
- Update student information
- File-based data storage
- OOP-based class design

🧠 Concepts Used

This project demonstrates:

- Object-Oriented Programming (Classes & Objects)
- Encapsulation (private data + getters/setters)
- File handling (ifstream / ofstream)
- String manipulation
- Basic CRUD operations

🗂 Student Data Fields

Each student record contains:

- Roll Number
- Name
- Subject
- Address

▶ How to Run

Open the project in a C++ compiler (CodeBlocks / Dev C++ / Visual Studio)

- Compile the program
- Run the executable
- Choose an option from the menu:

1 → Add Student
2 → Search Student
3 → Update Student
4 → Exit

📁 File Handling

- Student data is stored permanently in a text file
- Records are appended using ofstream
- Search reads from file using ifstream
- Update uses a temporary file to rewrite data safely
