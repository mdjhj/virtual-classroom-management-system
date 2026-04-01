# Virtual Classroom Management System

A web-based virtual classroom platform designed to facilitate remote learning and improve communication between teachers and students. The system enables course management, resource sharing, classroom interaction, and collaborative learning within an integrated online environment.

This project was developed as part of the **Software Engineering Sessional (CSE-434)** course at **Chittagong University of Engineering & Technology (CUET)**.

---

# Overview

The rapid adoption of digital learning during the COVID-19 pandemic highlighted the need for effective online education platforms. Traditional classroom systems often lack efficient communication, resource sharing, and student engagement.

The **Virtual Classroom Management System** addresses these challenges by providing a centralized platform where instructors and students can interact, share course materials, conduct live sessions, and manage classroom activities remotely.

---

# Key Features

### User Management
- User registration and authentication
- Role-based access (Teacher / Student)

### Course Management
- Teachers can create and manage courses
- Students can join courses using course IDs

### Classroom Interaction
- Announcement and post creation
- Comment-based discussion between teachers and students

### Learning Resources
- Upload and share course materials (PDF, slides, etc.)
- Students can download learning materials

### Live Classroom
- Teachers can initiate live sessions
- Students can join sessions and interact

### Activity Tracking
- Session history
- Classroom interaction records

---

# System Architecture

The system follows a **data-centered architectural model**, where a central database manages all classroom data while different modules interact with the system independently.

This architecture improves modularity, scalability, and maintainability.

### Architecture Diagram

*(Add your architecture diagram here)*

![System Architecture](docs/architecture_diagram.png)



---

# System Design

The system design includes several software engineering models and UML diagrams:

- Use Case Diagram
- Activity Diagram
- Class Diagram
- Sequence Diagram
- Component Diagram

These diagrams describe system functionality, data relationships, and interactions between different modules.

### Example Design Diagram

*(Add additional design diagrams if needed)*

![Design Diagram](docs/design_diagram.png)

---

# Screenshots

Below are example screenshots of the system interface.

### Login and Registration

![Login Page](screenshots/login.png)



### Teacher and Student Dashboard

![Dashboard](screenshots/dashboard.png)



### Course Page Interface

![Course Page](screenshots/course_page.png)



---

# Technology Stack

### Programming Language
- JavaScript

### Backend Runtime
- Node.js

### Web Framework
- Express.js

### Real-time Communication
- Socket.IO

### Video Communication
- WebRTC

### Development Tools
- Visual Studio Code

### Cloud Platform
- Heroku

---

# Testing

The system was evaluated using multiple software testing methods.

### Unit Testing
Modules tested include:
- Login
- Registration
- Course creation
- Post creation
- Session initiation

### White-box Testing
Control flow analysis and path testing were performed to verify internal logic.

### Black-box Testing
Functional testing was conducted to ensure the system met its requirements.

---

# Development Process

The project followed the **Waterfall Software Development Model** consisting of the following phases:

1. Requirement Analysis  
2. Planning  
3. System Modeling and Design  
4. Implementation  
5. Testing  
6. Deployment and Maintenance  

---

# Stakeholders

The system is designed to support the following stakeholders:

- Students
- Teachers
- Universities and colleges

The platform aims to improve accessibility, communication, and engagement in digital learning environments.

---

# Future Improvements

Possible future enhancements include:

- Enhanced video conferencing features
- Automated attendance tracking
- Online quizzes and assessments
- Learning analytics and performance tracking

---

# License

This project is licensed under the **MIT License**.
