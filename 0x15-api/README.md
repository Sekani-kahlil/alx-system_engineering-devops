image
ALX Software Engineering DevOps Track
Description
At ALX School we do hard things, the goal is not to be a good student rather the key goal is to be a good software Engineer. ALX_africa are on a mission to identify, develop and equip Africa’s next 3 million leaders. We have projects everyday that we have to push on GitHub in order for an automatic review to be done by Ubuntu 20.04 LTS. This repository contains directories each corresponding to a software engineering or DevOps project. These projects are part of the ALX Software Engineering year 1 curriculum. In these projects, we cover everything from the basics of the Linux Shell, Bash commands, Bash scripting, networking, APIs, and web-stack debugging to more advanced topics.

Table of contents
DIRECTORIES	DESCRIPTION
0x00-shell_basics	Introduction to the basics of the Linux Shell
0x01-shell_permissions	Introduction to Shell permissions and the file system
0x02-shell_redirections	Introduction to Shell redirections
API
Email: Messsagelordwill@gmail.com ##This project was further practice in working with API's. I collected data from the JSONPlaceholder REST API, and learned how to export it to either CSV or JSON format.

Tasks 📃
0. Gather data from an API

0-gather_data_from_an_API.py: Python script that returns information on the to-do list progress of a given employee ID.
Usage: python3 0-gather_data_from_an_API.py <employee ID>.
Output: Employee <employee name> is done with tasks(<# completed tasks>/<total # tasks>):
1. Export to CSV

1-export_to_CSV.py: Python script exports to-do list information of a given employee ID to CSV format.
Usage: python3 1-export_to_CSV.py <employee ID>
File name: <user id>.csv.
Format: "<user id>","<username>","<task completed status>","<task title>".
2. Export to JSON

2-export_to_JSON.py: Python script that exports to-do list information of a given employee ID to JSON format.
Usage: python3 2-export_to_JSON.py <employee ID>
File name: <user id>.json
Format: { "<user id>": [ {"task": "<task title>", "completed": <task completed status>, "username": "<username>"}}, ... ]}
3. Dictionary of list of dictionaries

3-dictionary_of_list_of_dictionaries.py: Python script that exports to-do list information for all employees to JSON format.
Usage: python3 3-dictionary_of_list_of_dictionaries.py
File name: todo_all_employees.json
