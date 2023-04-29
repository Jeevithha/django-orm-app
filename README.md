# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram
![image](https://user-images.githubusercontent.com/123623197/232503507-4283439b-b29b-4553-8fc4-6c3b01f45fad.png)

Include your ER diagram here

## DESIGN STEPS

### STEP 1:

clone the problem from github

### STEP 2:

create a new app

### STEP 3:

Enter the code for admin.py and model.py

### STEP 4:

Execute django admin and create 10 employees
## PROGRAM
```
Admin.py

from django.contrib import admin from .models import Employee,EmployeeAdmin

Models.py

from django.db import models class Employee(models.Model): 
Employee_id=models.CharField(max_length=8,help_text="Employee ID") 
Employee_name=models.CharField(max_length=100) Employee_post=models.CharField(max_length=100)
Employee_salary=models.IntegerField() Employee_age=models.IntegerField() Employee_email=models.EmailField()

class EmployeeAdmin(admin.ModelAdmin): list_display=
('Employee_id','Employee_name','Employee_post','Employee_salary','Employee_age','Employee_email')

Include your code here
```
## OUTPUT
Server Output:

![image](https://user-images.githubusercontent.com/123623197/235316746-a0e8406d-5d31-47d4-80a2-75c0717ff0d6.png)

Client Output:

![image](https://user-images.githubusercontent.com/123623197/235316737-10303e10-d10c-46f7-a0c5-bdb9aa929a7a.png)

Include the screenshot of your admin page.

## RESULT
program executed successfully
