# EduTrack-Powering the Future of Digital Classrooms
A powerful Spring Boot backend that powers student records, attendance, and subject management — clean, scalable, and integration-ready.

EduTrack is a robust and scalable Spring Boot REST API designed to streamline academic operations such as student management, subject enrollment, user authentication, and real-time attendance tracking.
Built using Java 17 and Spring Boot, this backend system follows a clean and modular architecture and is designed to integrate seamlessly with frontend frameworks like Angular or React. EduTrack is ideal for educational institutions, administrative dashboards, or full-stack learning platforms that need a secure and efficient backend.

## 🚀 Features

* Full CRUD operations for Students, Subjects, Users, and Attendance
* RESTful API endpoints using Spring Web MVC
* CORS enabled for frontend communication
* Modular MVC structure (Controller, Service, DAO, Entity)
* Built-in error handling with custom exceptions
* Ready for frontend integration and Postman testing

## 🧰 Tech Stack

* **Language:** Java 17
* **Framework:** Spring Boot, Spring MVC
* **Build Tool:** Maven
* **IDE:** Eclipse 
* **Server:** Embedded Tomcat (runs on port 8091)
* **API Tools:** Postman


## 🔗 API Endpoints

### 🎓 Student APIs

| Method | Endpoint                          | Description        |
| ------ | --------------------------------- | ------------------ |
| GET    | `/student/get-all-students`       | Fetch all students |
| GET    | `/student/get-student-by-id/{id}` | Get student by ID  |
| POST   | `/student/add-student`            | Add a new student  |
| PUT    | `/student/update-student`         | Update a student   |
| DELETE | `/student/delete-student/{id}`    | Delete a student   |

(Similar structure for `Subject`, `User`, and `Attendance` endpoints)

## ⚙️ Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/edu-track.git
   cd edu-track
   ```

2. Open in your IDE (Eclipse/IntelliJ)

3. Build the project:

   ```bash
   mvn clean install
   ```

4. Run the application:

   ```bash
   mvn spring-boot:run
   ```

5. Access the backend:

   * `http://localhost:8091/student/get-all-students`

---

## 🧪 Testing With Postman

Use the above endpoints in Postman. Ensure Spring Boot is running.

* You can create a Postman collection to test all endpoints.
* CORS is enabled for integration with Angular (`localhost:4200`).



## 🌱 Future Enhancements

* Role-based authentication with Spring Security
* JWT Token-based login system
* Swagger/OpenAPI integration for API documentation
* MongoDB/MySQL integration
* Deployment to cloud platforms (Render, Railway, AWS)

---

## 📌 License

This project is open source and free to use under the MIT License

## 🙌 Author

**Supriya Sukale**
Java Developer | Spring Boot Enthusiast | Full-Stack Learner

