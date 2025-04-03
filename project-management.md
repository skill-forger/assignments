# Project Management

## Description
The company needs to develop an system to manage employees and the projects they participate in. 
Each employee can be part of multiple projects, and each project can have multiple employees.

The company needs to track the following information:
- **Company**: Each company has a unique registration number, a specific name, and domain(e.g: abc.com).
- **Employee**: A company has multiple employees, but each employee belongs to only one company. 
The employee code in a company is unique.
- **Project**: An employee can work on multiple projects, and a project can have multiple employees.
An employee cannot be assigned to the same project twice, and must belong to the same company as the project.
Each employee's time on a project is logged with a start and end date.

## Use cases
### Company Management
- User can create a new company.
- User can update company details.
- User can remove a company.
- User can list all companies.
- User can view company details.

### Employee Management
- User can add a new employee to a company.
- User can update an existing employee’s information.
- User can remove an employee from a company.
- User can list all employees in a company.
- User can view employee details.

### Project Management
- User can create a new project in a company.
- User can update existing project details.
- User can remove a project from a company.
- User can list all projects in a company.
- User can view project details.
- User can list all projects of an employee are assigned to.
- User can assign employees to a project.
- User can remove employees from a project.
- User can track working hours of employees in a project.

