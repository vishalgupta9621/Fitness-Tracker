🏋️ Fitness Tracker Application

A full-stack Fitness Tracker Web Application built using Spring Boot, JPA (Hibernate), and JSP.
The application allows users to register, log in, create fitness goals, track workouts, and monitor their progress securely using session-based authentication.

🚀 Features

🔐 User Registration & Login (Session-Based Authentication)

🎯 Create, Update, Delete Fitness Goals

🏃 Track Workouts

📊 Dashboard to monitor progress

🗄️ Database integration using JPA (Hibernate)

🌐 JSP-based dynamic frontend

🔄 MVC Architecture (Controller → Service → Repository)

🛠️ Tech Stack
Backend

Java 17+

Spring Boot

Spring Data JPA (Hibernate)

Maven

Frontend

JSP

HTML5

CSS3

Bootstrap

Database

MySQL / PostgreSQL

📁 Project Structure
fitness-tracker/
│
├── src/main/java/com/fitness/tracker
│   ├── controller
│   ├── service
│   ├── repository
│   ├── dto
│   └── model
│
├── src/main/resources
│   ├── application.properties
│   └── static
│
├── src/main/webapp/WEB-INF/jsp
│
└── pom.xml
⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/your-username/fitness-tracker.git
cd fitness-tracker
2️⃣ Configure Database

Update application.properties

For MySQL:
spring.datasource.url=jdbc:mysql://localhost:3306/fitness_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
For PostgreSQL:
spring.datasource.url=jdbc:postgresql://localhost:5432/fitness_db
spring.datasource.username=postgres
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
3️⃣ Run the Application
mvn spring-boot:run

Application runs at:
http://localhost:8080
