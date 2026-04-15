# Patient Management System

This project is a **Patient Management System** built using **Java Spring Boot Microservices**.  
It provides features to manage patient records, appointments, and hospital operations efficiently.

## Features
- Patient registration and record management  
- Appointment scheduling  
- Microservices architecture for scalability  
- REST API integration  
- Secure authentication and authorization  
- Billing and analytics support  
- gRPC-based inter-service communication  

## Architecture

The system is composed of the following microservices:

| Service | Description |
|---|---|
| `api-gateway` | Single entry point for all client requests |
| `auth-service` | Handles authentication and authorization |
| `patient-service` | Manages patient records and data |
| `billing-service` | Handles billing and payment processing |
| `analytics-service` | Provides analytics and reporting |

## Tech Stack
- Java Spring Boot  
- Spring Cloud (Microservices)  
- gRPC (inter-service communication)  
- MySQL / PostgreSQL  
- Docker  

## Getting Started

### Prerequisites
- Java 17+
- Maven or Gradle
- Docker (recommended)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/harsharb05/patient-management-system.git
   ```

2. Navigate to the project folder:
   ```bash
   cd patient-management-system
   ```

3. Run the project using Maven/Gradle:
   ```bash
   ./mvnw spring-boot:run
   ```

   Or with Docker:
   ```bash
   docker-compose up
   ```

## API Documentation

REST API requests can be found in the `api-requests/` directory.  
gRPC request definitions are available in the `grpc-requests/` directory.

## Contributing
Feel free to fork this repository and contribute via pull requests.

## License
This project is licensed under the MIT License.
