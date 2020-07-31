# OS-Simulator
A web app that simulates various functions of an Operating System. It is built using the Django web framework and uses Python for backend calculations. Client Side scripts are primarily written in JavaScript and uses jQuery.

## Requirements

Django 3.x

## Running the server

In the root directory of the repo issue the following command<br>
`python manage.py runserver`


## Functionality

The front end sends Ajax POST requests to the Django server. The server runs the appropriate algorithm based on the flags provided in the POST request and returns the result. The JavaScript front end renders the result.

## Simulations/Algorithms included
1. Process Scheduling
2. Page Replacement
3. Memory Allocation
4. Disk Scheduling
5. File system structure
6. Banker's Algorithm
