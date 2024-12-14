Key Features of this program 

1-Add Employee
- Enter details like ID, Name, Position, Salary, and Email.
- Save data to a CSV file for persistence.

2-Update Employee:
- Modify specific fields without affecting others.

3-Delete Employee:
- Remove an employee by ID and update the CSV file.

4-Search Employee:
- Find employee details using a unique ID.

5-List All Employees:
- Display all employee records clearly.

6-File Handling:
- Use the csv module to store and retrieve data.
  
Technical Requirements:
- Python Basics: Variables, loops, conditionals, and functions.
- OOP Principles: Classes, objects, and encapsulation.
- File Handling: Persistent storage using CSV files.
- Error Handling: Validate inputs (e.g., numeric salary, valid email).
  
Structure:
- Employee Class: Represents a single employee and includes methods for managing attributes.
- EmployeeManager Class: Manages CRUD operations and handles CSV file interactions.
  
Final Words:
- Persistent Storage: Data is saved and loaded using a CSV file.
- Validation: The program checks for duplicate IDs during employee addition.
- Error Handling: Gracefully handles missing files and invalid inputs.
- Modularity: Encapsulated logic within the Employee and EmployeeManager classes.
- Scalable: Easily extendable for future requirements.
- Command-Line Interface (CLI): Menu-driven system for user interaction.
