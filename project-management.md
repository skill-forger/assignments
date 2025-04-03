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
- Manager/Admin can create a new company.
- Manager/Admin can update company details.
- Manager/Admin can remove a company.
- Manager/Admin can list all companies.
- Manager/Admin can view company details.

### Employee Management
- Manager/Admin can add a new employee to a company.
- Manager/Admin can update an existing employee’s information.
- Manager/Admin can remove an employee from a company.
- Manager/Admin can list all employees in a company.
- Manager/Admin can view employee details.

### Project Management
- Manager/Admin can create a new project in a company.
- Manager/Admin can update existing project details.
- Manager/Admin can remove a project from a company.
- Manager/Admin can list all projects in a company.
- Manager/Admin can view project details.
- Manager/Admin can list all projects of an employee are assigned to.
- Manager/Admin can assign employees to a project.
- Manager/Admin can remove employees from a project.
- Manager/Admin can track working hours of employees in a project.

