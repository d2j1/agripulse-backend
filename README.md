# Agripulse Project Collection

Welcome to the Agripulse Project Collection! This project is designed to support farmers by providing a platform where they can post their products for sale, search for products to buy, and manage rental requests. For example, if a farmer needs to rent a tractor for a day, they can easily find related posts. Similarly, farmers can post available rental equipment or services. While a tractor is used as an example, the platform supports a wide range of products and services.

## Project Overview

### Inspiration
I observed that farmers often struggle to advertise their services and products to a wide audience. This leads to fewer work opportunities and lower revenue, resulting in heavy loans and financial stress. Agripulse aims to bridge this gap by providing an easy-to-use platform for farmers to connect and transact.

### Completed Services
1. **UserService**
   - Implemented login, logout, and signup functionalities using Spring Security.
   - [UserService Repository](https://github.com/d2j1/agripulse-user-service)

2. **ContentService**
   - Completed CRUD operations for posts.
   - [ContentService Repository](https://github.com/d2j1/agripulse-content-service)

## Technologies Used
- Java, Spring Security
- Spring Boot
- Spring Data JPA
- MySQL
- JUnit
- Mockito
- Postman
- IntelliJ IDEA
- Maven

## Repositories

1. **UserService**  
   Repository for handling user-related operations, including authentication and authorization.
   - [UserService Repository](https://github.com/d2j1/agripulse-user-service)

2. **ContentService**  
   Repository for managing posts related to products and rental services.
   - [ContentService Repository](https://github.com/d2j1/agripulse-content-service)

## Getting Started

### Prerequisites
- Java 11 or higher
- Maven
- MySQL
- Postman (for testing)

### Running the Services
1. Clone the repositories:
   ```sh
   git clone link-to-UserService-repo
   git clone link-to-ContentService-repo
   ```

2. Navigate to each service directory and run the application:

```sh
cd UserService
mvn spring-boot:run
```
```sh
cd ContentService
mvn spring-boot:run
```
3. Use Postman or a similar tool to interact with the services.

## Contributing
We'd like to hear from you about contributions to improve Agripulse. Please fork the repositories and submit pull requests with detailed explanations of your changes.

## Contact
For any questions or suggestions, please open an issue in the respective repositories or contact me at [dhananjayjadhav2151@gmail.com].
