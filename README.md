# First Project Java Spring

## Description
This is a simple Spring Boot project created as part of an academic exercise. The project includes:
- A basic controller to handle HTTP GET requests.
- A static HTML page rendered using Thymeleaf.
- Static resources (e.g., images) for demonstration purposes.

## Project Structure
- **Main Class**: `FirstProjectJavaSpringApplication`
- **Controller**: `HelloController`
- **Static Resources**:
    - Images: `src/main/resources/static/images/logo.png`
- **Templates**:
    - Thymeleaf View: `src/main/resources/templates/greeting.html`

## How to Run the Project

### Prerequisites
1. Java 23 or compatible version installed.
2. Maven installed (or use the included `mvnw` wrapper).

### Steps
1. Clone the repository or download the project files.
2. Open the project in an IDE (e.g., IntelliJ IDEA, Eclipse).
3. Build the project:
   ```bash
   ./mvnw clean install
   ```
4. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```
5. Access the application in your browser at `http://localhost:8080`.

## Key Features
- **Basic Controller**:
  The `HelloController` handles the root URL (`/`) and serves a greeting message.
- **Thymeleaf Integration**:
  A dynamic HTML template (`greeting.html`) is rendered for `/greeting`.
- **Static Resource Handling**:
  Static files like images are served directly from the `static` directory.

## Example Usage
1. Navigate to `http://localhost:8080` to see the welcome message.
2. Visit `http://localhost:8080/greeting` to view a styled HTML page with an embedded image.
3. Visit `http://localhost:8080/greeting?name=your_name` to view a styled HTML page with an embedded image and your name.

## Technologies Used
- Java
- Spring Boot
- Thymeleaf
- Maven
