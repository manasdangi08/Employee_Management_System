# Employee_Management_System


## 📋 About The Project
This is a backend application built using **Java Spring Boot** that facilitates the management of employee records. It implements **Object-Oriented Programming (OOP)** principles and follows the **MVC (Model-View-Controller)** architecture.

The system allows users to perform full CRUD operations (Create, Read, Update, Delete) on employee data, which is persisted in a **MySQL** database.

## ✨ Features
* **Create:** Add new employees to the database.
* **Read:** Retrieve a list of all employees or search for a specific employee by ID.
* **Update:** Modify existing employee details (e.g., salary, designation, name).
* **Delete:** Remove an employee record from the system.

## 🛠️ Tech Stack
* **Language:** Java
* **Framework:** Spring Boot (Spring Web, Spring Data JPA)
* **Database:** MySQL
* **Build Tool:** Maven 
* **Tools:** Postman (for API testing), IDE (Eclipse)

## ⚙️ Prerequisites
Before running this project, ensure you have the following installed:
* Java Development Kit (JDK 17 or later)
* MySQL Server
* Maven or Gradle

## 🚀 Getting Started

### 1. Database Configuration
1.  Open MySQL Workbench or your command line.
2.  Create a database named `employee_db` (or your preferred name).
    ```sql
    CREATE DATABASE employee_db;
    ```
3.  Navigate to `src/main/resources/application.properties` and update your MySQL credentials:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/employee_db
    spring.datasource.username=root
    spring.datasource.password=your_password
    spring.jpa.hibernate.ddl-auto=update
    ```

### 2. Installation
1.  Clone the repository:
    ```bash
  [  git clone [https://github.com/your-username/employee-management-system.git](https://github.com/your-username/employee-management-system.git)](https://github.com/manasdangi08/Employee_Management_System.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd employee-management-system
    ```
3.  Run the application:
    ```bash
    mvn spring-boot:run
    ```

## 🔌 API Endpoints (Example)
| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `POST` | `/api/employees` | Create a new employee |
| `GET` | `/api/employees` | Get all employees |
| `GET` | `/api/employees/{id}` | Get employee by ID |
| `PUT` | `/api/employees/{id}` | Update employee details |
| `DELETE` | `/api/employees/{id}` | Delete an employee |

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!

