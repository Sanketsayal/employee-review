# Employee-Review-System
A full stack, app used for reviewing employee.

### Description

A full stack app, in which the admin, can assign the employees, to review each other on the basic of there work. The admin has special power, to make any other employee
as the new admin. Admin can also make the new employee, and they can also assing, the reviewer and revieweee. The admin can see the current employee, and according to the
review, the admin can remove the employee. The review given to the employee, is always going to be store in the database.


### Tech Stack

Node , Express, Mongodb , EJS , javaScript , html, css

### How to setup the project on local system

  1. Clone this project
  2. Start by installing npm if you don't have it already.
  3. Navigate to Project Directory.

After reaching the project directory you have to run the following the command.
   ```` 
        npm install 
        npm start || nodemon index.js
   ````
   
 # Admin Login First Time 
 pass: iamironman

#### If you want to make an employee as admin then use the secret key : monkey.

### Features

  You can review the employees. The admin has the special power to assing, the task to employee, remove the employee, add new admin, and also employee;
  
  
  # HomePage / Admin View
 ![Screenshot (60)](https://github.com/Sanketsayal/employee-review/assets/57364941/9e36a11f-bb0f-4a22-bb08-44e958852102)

  
  # Home page / Employee view
 ![Screenshot (61)](https://github.com/Sanketsayal/employee-review/assets/57364941/ea61bcd9-225b-405d-8081-2fab11cf0b2d)


  # Sign-In
 ![Screenshot (59)](https://github.com/Sanketsayal/employee-review/assets/57364941/3e671d84-ece8-47bc-af9b-6978d2176e06)
  
  # Assign Task
  ![Screenshot (62)](https://github.com/Sanketsayal/employee-review/assets/57364941/e2517a23-6719-4c78-bce8-846bdfa09d3a)


  # Employee List
![Screenshot (63)](https://github.com/Sanketsayal/employee-review/assets/57364941/6f7f0e90-d917-41db-8db7-90a90decaab9)


  

### Folder Structure

```
Employee Review System
    |
    |               |--->css
    |--->assets---->|--->images
    |             
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport-local-Stradegy.js
    |
    |                  |-->admin_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->review_controller.js
    |                  |-->user_controller.js
    |
    |               |-->review.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->admin.js
    |--->routes---->|-->index.js
    |               |-->review.js
    |               |-->user.js
    |
    |              |--->_header.ejs
    |              |---> addEmployee.ejs
    |              |---> admin.ejs
    |              |---> employe.ejs
    |--->views---->|--->forget_password.ejs
    |              |--->home.ejs
    |              |--->layout.ejs
    |              |--->sign_in.ejs
    |              |--->sign_up.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
    ````
