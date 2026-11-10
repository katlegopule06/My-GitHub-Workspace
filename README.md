# Section C: Dictionaries

## Project Title
Gradebook Management System – Section C

## Objective
The purpose of this section is to demonstrate the use of Python dictionaries for storing and managing student records.

## Features Implemented
- Add Student
- Update Student
- Delete Student
- Search Student
- Display Student Information

## Data Structure Used
A dictionary was used to store student records.

Example:

students = {
    "Jason": [45, 67, 96],
    "Katlego": [98, 85, 88]
}

The student's name acts as the key while the grades are stored as values.

## Program Operation
1. User selects an option from the menu.
2. Student information is stored in a dictionary.
3. Records can be searched, updated or deleted.
4. Student performance can be viewed at any time.

## Testing Conducted

### Test 1: Add Student
Input:
- Name: Jason
- Grades: 45, 67, 96

Result:
- Student added successfully.

### Test 2: Search Student
Input:
- Jason

Result:
- Student record displayed successfully.

### Test 3: Update Student
Input:
- Update Jason's grades

Result:
- Student record updated successfully.

### Test 4: Delete Student
Input:
- Delete Jason

Result:
- Student record removed successfully.

## Concepts Demonstrated
- Dictionaries
- Conditional Statements
- Loops
- Menu Systems
- Data Manipulation

## Conclusion
This section successfully demonstrates how dictionaries can be used to create a simple grade management system that allows users to add, update, delete and search for student records.


# Section E: Object-Oriented Programming

## Project Title
Gradebook Management System – Section E

## Objective
The objective of this section is to implement Object-Oriented Programming (OOP) principles using classes and objects.

## Classes Implemented

### Student Class

Attributes:
- Name
- Art Grade
- English Grade
- Social Studies Grade

Methods:
- calculate_average()
- display()

### Gradebook Class

Methods:
- add_student()
- remove_student()
- search_student()
- display_students()
- sort_students()

## Object-Oriented Concepts Used

### Encapsulation
Student information is stored within Student objects.

### Classes and Objects
A Student class and Gradebook class were created to manage the system efficiently.

### Methods
Actions such as displaying records and calculating averages are carried out through methods.

## Program Features

- Create Student objects
- Store Student objects in a Gradebook
- Search student records
- Remove student records
- Display all records
- Sort records alphabetically

## Testing Conducted

### Add Student
Result:
- Student object successfully created.

### Search Student
Result:
- Student located and displayed successfully.

### Remove Student
Result:
- Student deleted successfully.

### Sort Students
Result:
- Students sorted alphabetically.

## Concepts Demonstrated

- Classes
- Objects
- Constructors
- Methods
- Encapsulation

## Conclusion
Section E successfully demonstrates the application of Object-Oriented Programming principles by creating reusable classes that improve code structure and maintainability.

# Section F: Advanced Gradebook System

## Project Title
Gradebook Management System – Section F

## Objective
The objective of this section is to enhance the Object-Oriented Gradebook System by incorporating custom exceptions, searching algorithms, sorting algorithms and edge-case handling.

## Advanced Features Implemented

### Custom Exceptions

#### StudentNotFoundError
Raised when a student cannot be located.

#### InvalidGradeError
Raised when an invalid grade is entered.

## Searching Algorithm

### Linear Search

The program searches through the student list one record at a time until the requested student is found.

Advantages:
- Easy to implement
- Suitable for small datasets

## Sorting Algorithm

### Bubble Sort

Students are sorted alphabetically by name.

Process:
1. Compare adjacent students.
2. Swap when needed.
3. Repeat until sorted.

## Exception Handling

The program handles:

- Invalid grades
- Missing student records
- Invalid data types
- Menu selection errors

## Edge Cases Handled

### Duplicate Students
Prevents multiple records with the same name.

### Empty Gradebook
Displays appropriate messages when no student records exist.

### Invalid Grades
Rejects grades outside the range 0–100.

### Non-Numeric Input
Prevents program crashes through exception handling.

## Testing Conducted

### Test 1
Input:
- Grade = 105

Result:
- InvalidGradeError triggered successfully.

### Test 2
Input:
- Search for non-existent student

Result:
- StudentNotFoundError triggered successfully.

### Test 3
Input:
- Empty gradebook display

Result:
- Appropriate message displayed.

### Test 4
Input:
- Duplicate student record

Result:
- Student creation prevented.

## Concepts Demonstrated

- Object-Oriented Programming
- Custom Exceptions
- Bubble Sort
- Linear Search
- Error Handling
- Edge Case Handling

## Conclusion
Section F represents the completed Gradebook Management System and demonstrates advanced Python programming concepts including custom exceptions, searching algorithms, sorting algorithms and robust error handling techniques.
