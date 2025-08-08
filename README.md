---

# 🎓 Student Course Management System

A full-stack mini-project using Spring Boot REST API, PostgreSQL, and a responsive frontend built with HTML, CSS, and JavaScript. 
This project demonstrates the integration between backend and frontend using MVC architecture.

---

##  Features

-  Add a new student
-  View all students
-  Delete a student
-  Responsive UI
-  MVC Architecture
-  REST API integration
-  Uses PostgreSQL as the database

---

## Technologies Used

### Backend:
- Java + Spring Boot
- Spring Web, Spring Data JPA
- PostgreSQL
- Maven

### Frontend:
- HTML
- CSS
- JavaScript (Vanilla)

---

## 🗂 Project Structure

project-root/ │ ├── backend/ │   ├── controller/ │   ├── model/ │   ├── repository/ │   ├── service/ │   ├── resources/ │   └── StudentManagementApplication.java │ └── frontend/ ├── index.html ├── style.css └── script.js

---

## 🛠 How to Run

### 1️⃣ Prerequisites

```sql
- Java 17+
- PostgreSQL installed and running
- Maven

```
---

### 2️⃣ Setup PostgreSQL

```sql
Create a database named student_db.


CREATE DATABASE student_db;
```


---

---

###  3️⃣Backend Setup

Navigate to the backend folder and update the application.properties file with your DB credentials:

```sql
spring.datasource.url=jdbc:postgresql://localhost:5432/student_db
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```
Then run the backend:
```sql
./mvnw spring-boot:run
```
The API will be available at: http://localhost:8080/api/students


---
### 4️⃣ Frontend Setup

No build tools required. Simply open the index.html file in a browser:

```
cd frontend
open index.html  # Or double-click the file
```

---

### 🌐 API Endpoints

| Method         | Endpoint            | Descriptions      |
|----------------|---------------------|-------------------|
| GET            | /api/students       | Get all students  |
| POST           | /api/students       | Add a new student |
| DELETE         | /api/students/{id}  | Delete a student  |




---

---

### 📸 Screenshots


![op1](https://github.com/user-attachments/assets/ef22ff9d-e98b-4b23-a7c6-f55205641966)

---

---

## Author

Name: 1) Shruti Shivaji Kholgade
 2) Avantika Dashrath Firange


Email: 1) shrutikholgade@gmail.com
  2) firangeavantika07@gmail.com

       
GitHub: Shru19Kholgade



    





