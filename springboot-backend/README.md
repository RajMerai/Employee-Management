# Spring Boot Backend Application

## Project Overview
This is the backend part of our full-stack application built with Spring Boot.

## Prerequisites
- Java JDK 11 or higher
- Maven 3.6.x or higher
- Your favorite IDE (Spring Tool Suite, IntelliJ IDEA, or Eclipse)

## Setup Instructions
1. Clone the repository
```bash
git clone https://github.com/yourusername/springboot-backend.git
cd springboot-backend
```

2. Build the project
```bash
mvn clean install
```

3. Run the application
```bash
mvn spring-boot:run
```
The application will start on `http://localhost:8080`

## Project Structure
```
src/
  ├── main/
  │   ├── java/        # Java source files
  │   └── resources/   # Application properties and static resources
  └── test/            # Test files
```

## API Documentation
Once the application is running, you can access the API documentation at:
- Swagger UI: `http://localhost:8080/swagger-ui.html`
- API Docs: `http://localhost:8080/v2/api-docs`

## GitHub Integration
1. Initialize Git repository (if not already done)
```bash
git init
```

2. Add remote repository
```bash
git remote add origin <your-repository-url>
```

3. Push code to GitHub
```bash
git add .
git commit -m "Initial commit"
git push -u origin main
```

## Database Configuration
The application uses H2 database by default. To use a different database:
1. Update the database configuration in `src/main/resources/application.properties`
2. Add the appropriate database driver dependency in `pom.xml`

## Running Tests
```bash
mvn test
```

## Contributing
Please read CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests.

## License
This project is licensed under the MIT License - see the LICENSE file for details