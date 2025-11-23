📚 Student Management System – Java (OOP, Inheritance, Interfaces)

A complete Java-based Student Management System built using key Object-Oriented Programming principles:

Inheritance

Polymorphism

Abstract Classes

Interfaces

Method Overloading & Overriding

Final Class + Final Method

Collections (HashMap / List)

Modular Design (manager pattern)

This project is designed according to the requirements mentioned in Lab Assignment 2. It showcases clean OOP structure while keeping everything in one Java file for easy compilation.

🚀 Features ✔ Abstract Class – Person

Contains name, email

Has abstract method displayInfo()

✔ Student Class (extends Person)

Additional fields: rollNo, course, marks, grade

Overrides displayInfo()

Demonstrates method overloading with an extra display method

Includes a finalize() message (as required by assignment)

✔ RecordActions Interface

Defines all CRUD methods:

addStudent()

deleteStudent()

updateStudent()

searchStudent()

viewAllStudents()

✔ StudentManager Class

Implements the interface

Uses HashMap to prevent duplicate roll numbers

Overrides viewAllStudents() from AbstractManager

Adds sorting functionality

✔ Final Class + Final Method

Includes FinalNotice class to match assignment sample output.

✔ Interactive Menu System

Users can:

Add a student

Delete a student

Update course/marks

Search by roll number

View all students

Sort by marks (descending)

📦 Technologies & Concepts Used Concept Used? Inheritance ✔ Interfaces ✔ Abstract Class ✔ Polymorphism ✔ (static & dynamic) Method Overloading ✔ Method Overriding ✔ Final Class & Method ✔ HashMap & Lists ✔ Packages (Conceptually) ✔ OOP Design ✔ 📈 Learning Outcomes

After completing this project, you will understand:

How abstract classes enforce structure

How interfaces define contracts

How overriding & overloading differ

How polymorphism works in Java

How HashMap helps prevent duplicates

How to build modular OOP programs
