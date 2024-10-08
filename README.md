

# Simple Rest Service

## How to Run the Application

### Prerequisites

Make sure you have the following installed on your machine:
- **Java** (Version 11 or above)
- **Maven** (Version 3.6 or above)
- **IntelliJ IDEA** or any other preferred IDE

### Steps to Run

1. **Clone the Project**  
   Download the project files from the repository:
   ```bash
   git clone https://github.com/Kedarinath1502/springbootapp.git
   ```

2. **Navigate to the Project Directory**
   ```bash
   cd simple-rest-service
   ```

3. **Build the Project**  
   Use Maven to build the project:
   ```bash
   mvn clean install
   ```

4. **Run the Application**  
   Start the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```

   Alternatively, you can run the application by right-clicking on `SimpleRestServiceApplication` in your IDE and selecting "Run".

5. **Access the REST API**  
   Open your browser or use Postman and visit:
   ```
   http://localhost:8080/greeting
   ```

   Add a query parameter to customize the greeting:
   ```
   http://localhost:8080/greeting?name=YourName
   ```

### Default Port

The application will run on port `8080` by default. To change the port, edit `application.properties` located in `src/main/resources`.
