# MySQL JOIN Queries

## The Assignment

Help your manager to extract data and format it using join queries and MySQL functions. The exercises are below.

## Setup Instructions

1. Create assignment folder in terminal

  ```sh
  cd ~/muktek/assignments
  mkdir assignment--mysql-join-queries

  curl  https://raw.githubusercontent.com/muktek/assignment--mysql-join-queries/master/assignment-files/mysql-join-queries.sql > mysql-sub-queries.sql
  ```

2. Connect to MySQL Server on [45.55.135.14/phpmyadmin](45.55.135.14/phpmyadmin) and create your a copy of the database under your name. NOTE: Format name of should be `HR_«your-github-name»`.

  ```sh
  ssh root@45.55.135.14
    # enter password when asked
  ```


3. Inside mysql shell, connect to your HR_ database to complete the exercises (you should have one already from the previous exercise)
  ```sh
  mysql> mysql -u root -p
    # enter password when asked to

  # enter your database
  mysql> USE HR_yourGithubUsername
  ```

4. Check to see the tables are there

  ```sh
  mysql> SHOW TABLES;
  # =>
  +------------------------+
  | Tables_in_HR_«yourGithubUsername» |
  +------------------------+
  | Countries              |
  | Departments            |
  | Employees              |
  | JobHistory             |
  | Jobs                   |
  | Locations              |
  | Regions                |
  +------------------------+
  ```

4. You will need to write/record your queries in the `mysql-join-queries.sql` file

## Setup Instructions

  1. Connect to MySQL Server on [45.55.135.14/phpmyadmin](45.55.135.14/phpmyadmin)
  2. Copy the `HR` database and add your initial letters as suffix.

  ###### Example

  ```sql
  CREATE DATABASE HR_BG; # Bill Gates
  ```

## Exercise

```sql
# 1 Write a query to get the department name and number of employees
#   in the department.

# 2 Write a query to find the employee ID, job title, number of days
#   between ending date and starting date for all jobs in department 90
#   from job history.

# 3 Write a query to display the department ID and name and first name of manager.

# 4 Write a query to display the department name, manager name, and city.

# 5 Write a query to display the job title and average salary of employees.

# 6 Write a query to display job title, employee name, and the difference
#  between salary of the employee and minimum salary for the job.

# 7 Write a query to display the job history that was done by any employee who
#  is currently drawing more than 10000 of salary.

# 8 Write a query to display department name, full name (first_name, last_name),
#    hire date, salary of the manager for all managers whose experience
#    is more than 15 years.

```
