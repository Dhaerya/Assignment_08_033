# Assignment_08_033

# Student Management System

**Name**: Dhaerya More 

**PRN**: 23070126033

**Batch**: A2

## Overview

A simple command-line based student management system in Java, supporting:

- Add student
- Display all students
- Search student by PRN
- Error handling for invalid data and menu options

---

## Files

| File                        | Description |
|-----------------------------|-------------|
| `Main.java`                 | Entry point of the program |
| `Student.java`              | Student class with fields and toString() |
| `StudentOperations.java`    | Core logic: menu, add, display, search |
| `InvalidStudentDataException.java` | Custom exception for input validation |
| `InvalidChoiceException.java`      | Custom exception for invalid menu options |

---

## Exception Handling

- `InvalidStudentDataException` – Empty name/PRN or invalid age
- `InvalidChoiceException` – If user enters a menu option other than 1–4

---
