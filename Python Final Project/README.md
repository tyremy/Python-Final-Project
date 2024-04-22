# Tyler Remy CPSC 4970 Final Project - Curling League Manager
This project implements a user interface for managing a curling league. It provides the functionality to create leagues, teams, and members and associate members with teams and teams with leagues. 
It also provides the ability to import/export leagues as well as save and load the entire group of leagues. Leagues, teams, and members can all be added or removed and team members can be easily edited.

## Tools and Languages Used:

**Language:** Python</br>
**GUI Tool:** PyQt5

Python was used exclusively for this project to create the framework of the Curling League Manager and handle the logic behind the interaction of the various UI elements included. PyQT5 was used to create the user interfaces.

# How to Execute:
## Windows Instruction:

### Step 1:
Clone Project or Download Zip File and Extract

### Step 2:
Install Python 3.9
>https://www.python.org/downloads/release/python-3913/

### Step 3:
Run using batch file:
> Inside Python Final Project Folder right Click on "Curling_League_Manager.bat" file and run as administrator


## Mac Instructions

### Step 1:
Install Python 3.9
>https://www.python.org/downloads/release/python-3913/

### Step 2:
>Clone Project or Download Zip File and Extract

### Step 2:
Open Terminal and Navigate to Project</br>
Example:
> cd Dekstop/Python Final Project/'Python Final Project'

### Step 3:
Create Virtual Environment and activate using Virtualenv
>python3 -m pip install virtualenv
>virtualenv venv
>source venv/bin/activate

### Step 4:
Install Packages from Requirements.txt
>pip install -r requirements.txt

### Step 5:
Run Project
> python -m 'user_interface.main_window'


