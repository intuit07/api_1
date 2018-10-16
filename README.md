**Basic info:**
This app as a simple training task Manager with a rest-API without clientsas part
***
For install, you can use the file requirements.txt
***
**Dependencies:**
- Click==7.0
- Flask==1.0.2
- Flask-HTTPAuth==3.2.4
- itsdangerous==0.24
- Jinja2==2.10
- MarkupSafe==1.0
- pkg-resources==0.0.0
- Werkzeug==0.14.1
***
**Basic info**
This app like API, gives us the opportunity using the standard set of methods:
- method create_task - for create task
- method update_task - for update task
- method delete_task - for delete task  
- method get_task - get info of task 
- method get_tasks - get info of all tasks
- methods not_found, unauthorized - processing of errors 
- lib HTTPBasicAuth() - use for authorization
***
Work with service can be through the console, we can create, edit and view tasks used of the command
***curl -u miguel:python -i http://localhost:5000/todo/api/v1.0/tasks***
