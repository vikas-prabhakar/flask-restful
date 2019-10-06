# Docker container for simple Flask restful API
Make sure you have docker and docker-compose installed.

## Flask Restful API
A simple Flask Restful API using Flask-restful

## Description
- A simple Flask Restful API with following endpoints:
    - /add : **POST method**
    - /subtract : **POST method**
    - /multiply : **POST method**
    - /division :  **POST method**

- Posted data format
```
{
    "x": 12,
    "y": 20
}
```

- Response format
```
{
    "Message": <answer>,
    "Status Code": 200
}
```

## How to run
* $ docker-compose up
* Open your browser and type : http://localhost:5000/
* if helloworld appears then its working fine
* Test API using POSTMAN
