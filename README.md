# react-task-tracker
Task Tracker app built using React

Continuing on this project, using a mock json server to input data and deal with get, post, put and delete requests.

Install JSON Server with 

npm install -i json-server

Edit package.json to add server..using  "server": "json-server --watch db.json --port 5000"

```
 "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject",
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build",
    "server": "json-server --watch db.json --port 5000"
  },
  
 ``` 

Create a db.json file within project files, will with some data, such as this..

```
{
  "tasks": [
    {
      "text": "Meeting at School",
      "day": "!2th Feb 3pm",
      "reminder": true,
      "id": 1
    },
    {
      "text": "Dentist",
      "day": "13th Feb 2pm",
      "reminder": true,
      "id": 2
    }
  ]
}
```

