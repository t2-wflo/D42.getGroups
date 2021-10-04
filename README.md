# README
Device42 Audit groups

## Requirements:
  device42 credentials
	Python3
	- openpyxl
	- requests
	- urllib3
  - string

This will put all the Device42 groups and users into an excel sheet, the columns will be the groups and the rows will have the users.


## How to use.
Create an python virtual environment. In this example I will create a directory called getGroups.
```bash
python3 -m venv getGroups
```

Copy the getGroups.py file into the 'getGroups' virtual environment directory. Enter in your device42 credentials.
NOTE: If you want to see all the group you will need admin access.

Go into your python enviornment
```bash
cd getGroups
source bin/activate
```

Install the python modules needed.
```bash
pip3 install requests
pip3 install openpyxl
```

Run the script, it will create an excel file into the same directory as the script.
```bash
python3 getGroups.py
```
