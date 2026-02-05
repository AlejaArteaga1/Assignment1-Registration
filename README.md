# Course Registration – Spring Boot Application

## Description
This project is a simple Spring Boot web application developed using **Spring MVC** and **Thymeleaf**.  
It allows a student to fill out a course registration form and view a confirmation page displaying the submitted information.
The application was created as part of **Assignment 1** and follows the MVC (Model-View-Controller) design pattern.
No database is used; the data is handled temporarily using model attributes.

---

## Project Structure
src
└── main
├── java
│ └── com.example.registration
│ ├── RegistrationApplication.java
│ ├── controller
│ │ └── RegistrationController.java
│ └── model
│ └── Student.java
└── resources
├── static
│ └── style.css
├── templates
│ ├── register.html
│ └── confirmation.html
└── application.properties

---
## Application Features
- Displays a registration form for students
- Accepts user input (name, email, course, and level)
- Processes form submission using Spring MVC
- Redirects to a confirmation page (`/confirmation`)
- Displays submitted data using Thymeleaf
- Includes basic CSS styling
- No database required

---

## How to Run the Application

1. Clone or download the project
2. Open the project in **IntelliJ IDEA** or **Eclipse**
3. Make sure Maven dependencies are loaded
4. Run the application from:
RegistrationApplication.java

5. Open a web browser and go to:
http://localhost:8080/register

---

## Available URLs
- **Registration Form:**  
`http://localhost:8080/register`

- **Confirmation Page:**  
`http://localhost:8080/confirmation`  
(Accessed automatically after form submission)

---

## Notes
- The confirmation page follows the assignment requirement to use the `/confirmation` endpoint.
- Data is passed between pages using `ModelAttribute` and `RedirectAttributes`.
- This project focuses on understanding Spring MVC and Thymeleaf fundamentals.
