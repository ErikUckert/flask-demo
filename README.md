# flask-demo
This Project is about building a small web application with flask. It's a simple "Todo" App, where you can create, update or delete tasks.

### How to run the app and create a new database for the tasks

#### 1 - CREATE A DATABASE
##### open python shell

```
python3
```

##### import db

```
from app import db
```

##### create database
```
db.create_all()
```

#### 2 - RUN THE TASKMASTER WEB APP

##### if you are already in the python shell, exit it

```
exit()
```

##### start server with

```
python3 app.py
```

##### visit web app under 
```
localhost:5000
```

