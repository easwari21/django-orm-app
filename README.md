# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:

Created table and inserted values to it in the django applications

### STEP 2:

Implementation of python code in README.md file

### STEP 3:

Uploading the necessary files

### STEP 4: 

Pushing it to the github account

## PROGRAM

```
from django.db import models

# Create your models here.
from django.db import models
from django.contrib import admin
# create your models here
class hangout(models.Model):
    visitorname = models.CharField(max_length=10,primary_key=True)
    visitorage = models.IntegerField()
    pickuplocation = models.CharField(max_length=50)
    venue = models.CharField(max_length=30)
    numberofperson = models.IntegerField()

class hangoutAdmin(admin.ModelAdmin):

    list_display = ('visitorname','visitorage','pickuplocation','venue','numberofperson')
Include your code here
```
## OUTPUT
![output](https://github.com/easwari21/django-orm-app/assets/131534979/b337ebf9-b549-4e64-9bb0-4663a3798bf8)


## RESULT

The program is successfully executed
