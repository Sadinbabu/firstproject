# firstproject
Project Description
This project is Task 1 for the Spring Framework Apps assignment. The goal is to create a basic
Spring Boot application with a controller, handle HTTP requests, and return both plain text and
HTML views using the MVC pattern.
Technologies Used
• Java
• Spring Boot
• Spring Web
• Thymeleaf
• Maven
How to Run the Application
1. Open the project in IntelliJ IDEA
2. Reload Maven dependencies
3. Run Task1Application.java
4. Application runs on port 8080
Endpoints
GET /hello – returns plain text using @ResponseBody
GET /greeting – returns HTML view rendered with Thymeleaf
Used Annotations
@SpringBootApplication – application entry point
@Controller – MVC controller
@GetMapping – mapping HTTP requests
@ResponseBody – returning plain text
MVC Pattern
Model – data passed from controller
View – greeting.html rendered by Thymeleaf
<img width="2248" height="1308" alt="Screenshot 2025-12-22 180343" src="https://github.com/user-attachments/assets/9390141a-015f-4aa9-ba18-41c1a6125ca1" />

Controller – handles HTTP requests
