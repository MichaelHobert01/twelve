# Command-line Application
This command-line application allows users to manage departments, roles, and employees in a database. Users can perform various operations such as viewing departments, roles, and employees, adding departments, roles, and employees, as well as updating an employee's role.

# Table of Contents
Installation
Usage
Options
Examples
Contributing
License

# Installation
To install and set up the application, follow these steps:

Clone the repository to your local machine.
Navigate to the project directory.
Install the required dependencies by running the following command:
Copy code
npm install
Set up the database by executing the provided SQL scripts to create the necessary tables and populate initial data.
# Usage
To start the application, run the following command:

Copy code
node app.js
Options
Upon starting the application, you will be presented with the following options:

View all departments
View all roles
View all employees
Add a department
Add a role
Add an employee
Update an employee role
Select the desired option by entering the corresponding number or letter.

Examples
View all departments
Choose the option to view all departments, and you will be presented with a formatted table displaying the department names and IDs.

View all roles
Select the option to view all roles, and you will see a table showing the job titles, role IDs, associated departments, and salaries for each role.

View all employees
Choose the option to view all employees, and a formatted table will be displayed, containing employee data such as IDs, first names, last names, job titles, departments, salaries, and the managers they report to.

Add a department
To add a new department, select the corresponding option. You will be prompted to enter the name of the department, and upon submission, it will be added to the database.

Add a role
Select the option to add a role. You will be prompted to provide the name, salary, and department for the new role. Once entered, the role will be added to the database.

Add an employee
Choose the option to add an employee. You will be prompted to enter the employee's first name, last name, role, and manager. Upon submission, the employee will be added to the database.

Update an employee role
To update an employee's role, select the option to update an employee role. You will be prompted to choose an employee to update and provide their new role. The employee's information will be updated in the database accordingly.

# Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to submit a pull request.

# License
This project is licensed under the MIT License.