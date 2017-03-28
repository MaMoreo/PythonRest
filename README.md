# PythonRest
A simple RESTFul application written in Python

This project is based in "Designing a RESTful API with Python and Flask" article posted by Miguel Grinberg  https://blog.miguelgrinberg.com/post/designing-a-restful-api-with-python-and-flask 

Contents:
- Flask virtualenv
- app.py: the RESTful web service

Use:
- activate the virtual enviroment from: flask/Scripts/activate
- run the application with >app.py
- use the API from a Web Browser or with curl from a command line:
 
  - GET	    http://localhost/todo/api/v1.0/tasks	          Retrieve list of tasks
  - GET	    http://localhost/todo/api/v1.0/tasks/[task_id]	Retrieve a task
  - POST	  http://localhost/todo/api/v1.0/tasks	          Create a new task
  - PUT	    http://localhost/todo/api/v1.0/tasks/[task_id]	Update an existing task
  - DELETE	http://localhost/todo/api/v1.0/tasks/[task_id]	Delete a task
  
Hint:
  The GET methods are protected by password: miguel/python

Todo:
  - Change the service to HATEOAS (return a link to the use not an id).
  - Replace the in-memory database with a real one.
