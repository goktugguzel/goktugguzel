# Employee Management System

This C program simulates a basic employee management system. The program uses a linked list to add, delete, display, and search for employee information.

## Usage

The program operates interactively through a menu that provides users with a series of options as ;

1. **Add an employee:** Option to add a new employee. User input includes the employee's name, ID, position, and salary.

2. **Delete an employee:** Option to remove an employee from the list. User input includes the name of the employee to be deleted.

3. **Display the list:** Option to display all employees in the order they are stored in the list.

4. **Search for an employee:** Option to search for an employee by name.

5. **EXIT:** Option to exit the program. Memory is freed at the end of the program.

## Posible Errors 

1. While choosing an option in the main menu, when user insert an invalid input, system will warn user to insert a number.

2. Also in the same part, when user insert a number that is not in the menu as an option, system will warn user to insert a proper number. 

3. After choosing "Add an employee" in main menu, if user wants to add a new employee who has a name that is already in the list, system will warn user.

4. After choosing "Delete an employee" in main menu, if the employee list is empty, then system will warn user.

5. After choosing "Display the list" in main menu, if the employee list is empty, then system will warn user.
  
6. After choosing "Search for an employee" in main menu, if the employee that user inserted is not in the list, system will warn user
