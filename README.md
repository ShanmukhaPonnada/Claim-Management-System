# Claim-Management-System

# Insurance Claim Management System

A full-stack insurance claim management application designed to simplify insurance policy administration, claim submission, verification, and status tracking.

## Tech Stack

- Backend: Java 17, Spring Boot, Spring Data JPA, Hibernate
- Frontend: React.js, JavaScript, HTML5, CSS3
- Database: PostgreSQL
- Security: Spring Security, JWT, Role-Based Access Control
- Testing: JUnit 5, Mockito, Postman
- DevOps: Git, GitHub, Docker, GitHub Actions
- Documentation: Swagger/OpenAPI

## Key Features

### Customer Module
- Customer registration and secure login
- View insurance policies and coverage details
- Submit insurance claims
- Upload supporting documents
- Track claim status and history

### Insurance Officer Module
- View and review submitted claims
- Verify policy details and supporting documents
- Approve or reject insurance claims
- Update claim status
- Manage customer claim records

### Security
- JWT-based authentication
- Role-based authorization
- Input validation and exception handling
- Secure REST API access

## System Architecture

React.js Frontend
        |
        v
Spring Boot REST APIs
        |
        v
Controller → Service → Repository
        |
        v
PostgreSQL Database

## REST API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | Register customer |
| POST | /api/auth/login | Authenticate user |
| GET | /api/policies | Retrieve policies |
| POST | /api/claims | Submit a claim |
| GET | /api/claims/{id} | Track claim status |
| POST | /api/claims/{id}/documents | Upload documents |
| PATCH | /api/claims/{id}/status | Update claim status |

## Software Development Lifecycle

1. Requirement analysis and system design
2. Database schema and REST API design
3. Backend and frontend development
4. Unit and integration testing
5. Debugging and code review
6. Docker containerization
7. CI/CD automation and deployment
8. Application monitoring and maintenance

## Testing

- Unit testing using JUnit and Mockito
- REST API testing using Postman
- Integration testing for claim workflows
- Authentication and authorization testing
- Validation and exception-handling tests

## Deployment

The application is designed to support Docker-based deployment and automated build and testing workflows using GitHub Actions.

## Future Enhancements

- AI-powered claim assistance using Spring AI
- RAG-based insurance policy document search
- Email notifications for claim status updates
- Claim processing analytics dashboard

## Author

Shanmukha Ponnada

Java Full Stack Developer
