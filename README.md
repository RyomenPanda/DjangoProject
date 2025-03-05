# DjangoProject
## Simple Django Project for Beyond Curriculum Training.

This project is purely a prototype for a basic Student Management Authentication system.


# RECOMMENDED TO RUN IN A VIRTUAL PYTHON ENVIRONMENT!!

### **How to set up and run the project:**

- Open terminal in root folder and run ``` python -m venv venv ``` [Creates the Virtual Environment]
- Activate the Virtual Environment ``` venv\Scripts\activate ``` [In case it throws an error, Run Powershell as an administrator and use ``` Set-ExecutionPolicy RemoteSigned ``` and press 'Y' when prompted.]
- With the Virtual Environment now running, run ``` pip install django ``` & ``` pip install setuptools ```
- After everything's done, run ``` python manage.py migrate ``` to migrate
- Finally run ``` python manage.py runserver ``` to run the server on local host.
