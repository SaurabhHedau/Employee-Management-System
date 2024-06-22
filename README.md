# Employee-Management-System
Employee Management System that provides facility to manage employees of any organization.

To implement the Employee Management System using Object-Oriented Programming principles and appropriate data structures, we can follow these steps:

Create an Employee class: This class will have attributes for employee ID, name, department, and salary. It will also include methods to update these attributes.

Use a HashMap to store employee data: We can use a Python dictionary to store employee objects, where the key is the employee ID and the value is the employee object.

Implement exception handling: Handle cases where the user inputs invalid data, such as a non-existent employee ID.

Provide a user-friendly console interface: Create a menu-based console interface for the user to interact with the system.

Explanation
#Employee Class:

Holds employee details.
Methods to update attributes.
EmployeeManagementSystem Class:

Manages a dictionary of employees.
Methods to add, update, delete, display, and search employees.
main Function:

Console interface with options for the user to interact with the system.
Takes user input, processes it, and calls appropriate methods.
Exception Handling
Handled cases where the employee ID does not exist in the system.
Checked for duplicate employee IDs during addition.
User Interface
Provided a menu-driven interface for ease of use.
Ensured the system runs in a loop until the user chooses to exit.
