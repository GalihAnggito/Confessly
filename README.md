# Confessly 🤫

Confessly is an Anonymous Confession Platform developed as a Final Project for the Object-Oriented Programming Course (Tugas Besar PBO). It allows users to share their thoughts and confessions anonymously in a safe and engaging environment.

## 👥 Team Members

This project is proudly built by:
- Rizky
- Abay
- Arya
- Aryo
- Mahar

## 🛠️ Tech Stack

This application is built using a modern Java stack:

*   **Backend:** Java 17, Spring Boot, Spring Web
*   **Data Access:** Spring Data JPA
*   **Database:** MySQL
*   **Template Engine:** Thymeleaf
*   **Other Tools:** Lombok, Maven

## 🚀 Getting Started

### Prerequisites

*   Java Development Kit (JDK) 17 or higher
*   Maven 3.6+
*   MySQL Server

### Installation & Setup

1.  **Clone the repository** (if you haven't already):
    ```bash
    git clone <repository-url>
    cd Confessly
    ```

2.  **Configure the Database:**
    *   Create a MySQL database (e.g., `confessly_db`).
    *   Update your `src/main/resources/application.properties` or `application.yml` with your MySQL credentials:
        ```properties
        spring.datasource.url=jdbc:mysql://localhost:3306/confessly_db?serverTimezone=UTC
        spring.datasource.username=your_mysql_username
        spring.datasource.password=your_mysql_password
        spring.jpa.hibernate.ddl-auto=update
        ```

3.  **Build the application:**
    ```bash
    mvn clean install
    ```

4.  **Run the application:**
    ```bash
    mvn spring-boot:run
    ```

5.  **Access the application:**
    Open your web browser and navigate to `http://localhost:8080`.

## 📁 Project Structure

*   `controller`: Handles incoming web requests and routes.
*   `service`: Contains business logic.
*   `repository`: Interfaces for database operations (Data Access Layer).
*   `model`: Entity classes representing database tables.
*   `dto`: Data Transfer Objects for transferring data between client and server.
*   `config`: Application configuration files.
*   `exception`: Custom error and exception handling.

## 📝 License

This project is created for educational purposes (TUBES PBO).
