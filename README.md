# Student Management
This is a Student Management Program made with Java using MySQL as the backend database

# Features:
- View the list of all students
- Filter and search the list of students
- Add or Delete a student
- Edit the details of a student

# Preview:
<details>
  <summary>All Students</summary>
  <img alt="View All Students" src="https://github.com/user-attachments/assets/b7bd4a87-56c9-46b8-b013-06e6507a5466">
</details>

<details>
  <summary>Add or Delete a Student</summary>
  <img alt="Add or Delete" src="https://github.com/user-attachments/assets/f7f24e4f-8fd8-4299-acab-b55e2b9e686c">
</details>

<details>
  <summary>Edit a Student</summary>
  <img alt="Edit a Student" src="https://github.com/user-attachments/assets/85ea409b-a3e5-4f70-9406-83cf8af00a1b">
</details>

# Creating the required database:
- Create the database `school`:
  ```mysql
  CREATE DATABASE school;
  ```
- Create the table `students`:
  ```mysql
  CREATE TABLE students (
    class int,
    roll_no int,
    first_name VARCHAR(256),
    last_name VARCHAR(256),
    date_of_birth DATE,
    gender CHAR(1)
  );
  ```
