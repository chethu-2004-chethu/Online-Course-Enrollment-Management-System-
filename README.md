# 🎓 Course Enrollment System

A full-stack **Spring Boot-based Course Enrollment System** that allows admins to manage courses and students, and students to enroll in courses. Built using the **Spring Boot framework** and follows **MVC architecture**.

## 🚀 Features
- **Admin Panel**:
  - Add/update/delete courses
  - Manage student records
  - View enrollment data

- **Student Panel**:
  - View and enroll in courses
  - Track own enrollments

## 🛠️ Tech Stack
- **Backend**: Java 8, Spring Boot, Spring Data JPA, Hibernate
- **Database**: MySQL
- **Build Tool**: Maven

## 📁 Project Structure
Course-Enrollment-System/
├── src/
│ ├── main/
│ │ ├── java/com/SpringBoot/
│ │ │ ├── Controller/
│ │ │ ├── Entities/
│ │ │ ├── Repository/
│ │ │ ├── Service/
│ │ │ └── Application.java
│ └── resources/
│ └── application.properties
├── pom.xml


## ⚙️ Setup Instructions
1. **Clone the repository**  
   `git clone https://github.com/your-username/Course-Enrollment-System.git`

2. **Create MySQL Database**  
   - Name: `course_enrollment`
   - Update `src/main/resources/application.properties`:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/course_enrollment
     spring.datasource.username=root
     spring.datasource.password=your_password
     spring.jpa.hibernate.ddl-auto=update
     ```

3. **Build & Run**  

4. **Access APIs**  
- Admin: `/admin/...`
- Student: `/student/...`

## 🔮 Future Scope
- JWT Authentication & Role-based access
- Frontend using React/Angular
- Email alerts for course enrollment
- Docker deployment

----------------------------------------

👨‍💻 Developed by Chethan K


