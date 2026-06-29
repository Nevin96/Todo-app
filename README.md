# 📝 Todo Application

A simple and intuitive **Todo Application** built using **Spring Boot**, **Thymeleaf**, and **MySQL**. The application allows users to manage their daily tasks through a clean and responsive web interface.

---

## 📸 Application Preview

![Todo Application UI](screenshots/home.png)

> **Note:** Save the screenshot above as `home.png` inside a folder named `screenshots` in your repository for the image to appear on GitHub.

---

## ✨ Features

- ➕ Add new tasks
- ✅ Toggle task completion status
- 🗑️ Delete existing tasks
- 📋 View all tasks
- 💾 Store tasks persistently using MySQL
- 🎨 Simple UI built with Thymeleaf and Bootstrap

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Java | Programming Language |
| Spring Boot | Backend Framework |
| Spring Data JPA | Database Operations |
| Hibernate | ORM |
| Thymeleaf | Server-side Templating |
| MySQL | Database |
| Bootstrap | User Interface |
| Maven | Dependency Management |

---

## 📁 Project Structure

```
src
├── main
│   ├── java
│   │   ├── controller
│   │   ├── model
│   │   ├── repository
│   │   ├── service (optional)
│   │   └── TodoappApplication.java
│   └── resources
│       ├── static
│       ├── templates
│       └── application.properties
```

---

## 🚀 Getting Started

### Prerequisites

- Java 17 or above
- Maven
- MySQL Server
- Git

### Clone the Repository

```bash
git clone https://github.com/Nevin96/Todo-app.git
cd Todo-app
```

### Create the Database

```sql
CREATE DATABASE todo_app;
```

### Configure Database

Create an `application.properties` file inside:

```
src/main/resources/
```

Example configuration:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/todo_app
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

### Run the Application

Using Maven:

```bash
mvn spring-boot:run
```

Or run the `TodoappApplication` class from your IDE.

---

## 🌐 Access the Application

Open your browser and visit:

```
http://localhost:8080
```

---

## 🎯 Available Operations

- Add a new task
- Mark a task as completed or incomplete
- Delete a task
- Automatically save all changes to the MySQL database

---

## 🔮 Future Improvements

- ✏️ Edit existing tasks
- 📅 Due dates
- 🔍 Search tasks
- 📂 Task categories
- 👤 User authentication
- 📱 Responsive mobile layout
- 🌐 REST API support

---

## 👨‍💻 Author

**Nevin Babu**

- GitHub: https://github.com/Nevin96

---

## ⭐ If you found this project helpful, consider giving it a star!
