# Employee-Review-System
This is an Employee Review System project of Coding Ninjas made using Nodejs, Expressjs in backend. MongoDB is used for database and for frontend it uses EJS. Any user can create their account with role either admin or employee. Both Admin and Employee is given different task.
  Admin can add, remove or update any user's data. Employee can give their feedback on other employees.

  # Installation and Run 
  Follow these steps:
  - Get the code on your system.
  . Now clone this repository
```go
git clone https://github.com/wizzenalum/employee-review-system.git
```
  - Open terminal on your pc and navigate to the root directory of the project.
 
  -  Install dependencies
```go
npm install --save
```
  - Create a '.env' file inside root directory and define values for
      - PORT ( port on which your project will run )
      - MONGODB_URL ( URL of your mongoDB database for connecting to database )
      - SECRET_KEY ( secret key for express-session )
  -  That's... it  run the application
```go
npm start
```
  - Open your web browser and serach for 'localhost:{PORT}/' to see the output.

# Features
This application has following features with three views
1. Admin view
```sh
Add/remove/update/view employees
Add/update/view performance reviews
Assign employees to participate in another employee's performance review
```
2. Employee view
```sh
List of performance review requiring feedback 
An employee can register, only admin can make an employee an admin
```
3. sign in for admin and user.
```sh
also has super user for initialting the application once
Make 1 login for admin and employee
```
  - Create account with your role as " Admin / Employee "
  - Login using your email and password.
  - Store your session-token in DB so that logged in user's session will be safe.
  - Store all the data of employee, reviews in database.
  - Admin:
      - View list of all the employee.
      - Add a new employee.
      - Update data of any employee ( Name, email, Role ).
      - See review given to an employee.
      - Assign task to any employee ( review task : Giving review to other employee )
      - Delete any employee.
  - Employee:
      - See all the reviews given to him by other employee.
      - Give his review for other employee as assigned from admin.
  
# Tools used:
  - Nodejs
  - Expressjs
  - MongoDB
  - EJS
  - Passport
  - Passport local
  - BootStrap
