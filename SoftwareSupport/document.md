
# Contents
	1.	Requirements
	2.	Details of UI Components
	3.  How Users Use This Program?

---

<br>

## 1. Requirements

This program applies **CRUD** operations with a GUI for the users. There are 3 columns, 'ID', 'username', 'email' and 'Enable'. The roles that can be given to the people in the database are 'Super Admin', 'Admin', and 'Guest'. Super Admin role is must to manage the records and users, however, its name can be changed. **Only one** super admin role can be present in the database, and it can specify the privileges of the other roles. Super admin role **cannot remove** itself but **can modify itself** excepts its **role**.
**New columns** and **roles** can be added, and current roles **can be modified** by the users **according to privileges** of the roles. Furthermore, the program allow the user to determine the number of columns displayed in the program.
The program can be look like 
![gui](/gui.png)


---
<br>

## 2. Details of UI Components ##
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2.1.	**Main Screen**: This component can be divided into two parts:
	-	On the left side, program displays the records in the database.
	-	On the right side, a form to add a new record to database.
	Program must allow the user to customize to screen if there are more columns in the database. In this case, program must fill the whole screen, and whenever user hits the new user button, a new window should appear to add new record.

<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.2.	**New User Button**: It is a button to add a new user. The behaviour of this button must satisfy the rules mentioned in *section 2.1 Main Screen*.

<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.3 **Enable Checbox**: It enables the record if it is checked. 

<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.4 **Save User**: It saves the record with the information in the *form* elements. Program should allow the user to determine the rules of each information, such as 'username field must have at most 20 charachters'. The new user is added to database and displayed in the area in which the records are displayed.

<br>

---

<br>

## 3. How Users Use This Program
Those who use this program for the first time **have to add a super admin role** to their database. One option for the user is that user can create a JSON file and fill the related records for super admin role, and paste this file to specified location or add this file by the program.
Those who have already used this program can simply login by a simple login page.
