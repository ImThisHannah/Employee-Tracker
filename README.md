# 10 SQL: Employee Tracker

 
Developers frequently have to create interfaces that allow non-developers to easily view and interact with information stored in databases. These interfaces are called **content management systems (CMS)**. This is to build a command-line application from scratch to manage a company's employee database, using Node.js, Inquirer, and PostgreSQL.

## User Story

```md
AS A business owner
I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business
```
## Application
Open terminal window after fork. npm init -y to create a package.son file to store your dependenices.

npm i to install your NPM package manager and required dependencies.

npm i inquirer to interact with the user via the command-line.

npm i figlet to implement FIGfont spec in Javascript.

npm i chalk for terminal string styling of Logo.

npm i console.table to print MySQL rows to the console.

npm i dotenv to store environmental variables.

npm i mysql2 to connect to your MySQL database and perform queries.

run command mysql -u -root -p to initilize MySQL, then type username and password to login:

```Test User

username: Tester1
password: Test1234
database: employeeTracker_db
```
Welcome to the MySQL monitor

```type mysql> status to confirm connection with database.```

run command node employeeTracker, or npm start to answer the prompts.

## Mock-Up
![alt text](2025-01-07.png)
The following video shows an example of the application being used from the command line:
[Employee.webm](https://github.com/user-attachments/assets/fab4626a-802e-4c32-8944-4b30035f7100)
