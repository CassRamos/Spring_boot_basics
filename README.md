<h1 align="center">Spring boot 🍃 - Student management  </h1>

<p align="center">
A simple application using Java and Spring<br/>
</p>

<p align="center">
  <a href="#-tecnologies">Tecnologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>


<br>

## 🚀 Tecnologies

This project was developed with the following technologies:

- Java & Spring framework
- Postgres
- Git & Github
- Postman (to endpoints)

## 💻 Project

The Student management is an application responsible for implementing CRUD (create, read, update, delete) on a Student object


## :memo: License

This project is under license from MIT


## Endpoints

### GET (all students):

```
http://localhost:8080/api/v1/student
```

### POST (create student):

```
http://localhost:8080/api/v1/student


JSON:
  {
    "name": "{{$randomFirstName}}",
    "email": "{{$randomEmail}}",
    "dob": "2002-06-30"
  }
```

### PUT (update student):

```
http://localhost:8080/api/v1/student/<student Id>


JSON:
  {
    "name": "{{$randomFirstName}}",
    "email": "{{$randomEmail}}",
    "dob": "2002-06-30"
  }

**Only one object property is required for student update**
```


### DELETE:

```
http://localhost:8080/api/v1/student/<student Id>
```






