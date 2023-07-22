# UserManagement - Spring Boot

## Introduction
This is a small UserManagement where we perform crud operation with user information.
## Technologies Used
- Java-17
- Spring Boot
- Maven (for project build)
##  Data Flow

* Controller -
  it Will receive request from client and send request to service layer.
* Service -
  it Will receive request from controller and this will manipulate the operation and send request to DAO layer
* Repository -
  it Will receive request from service and it will communicate with the pogo

##  Data Structure used in project

* DataBase Design -
  Here Created pogo for user.
  In this project mostly used ArrayList & along with java 8 feature like optional class and
  lambda expression.


## Setup and Installation
1. Clone the repository to your local machine using `git clone`.
2. Ensure you have Java JDK and Maven installed on your system.
3. Open the project in your favorite IDE (IntelliJ, Eclipse, etc.).
4. Build the project using Maven: `mvn clean install`.
5. Run the Spring Boot application: `mvn spring-boot:run`.

## API Endpoints

### Controller Endpoints:
- `UserController`: Here we're performing CRUD operations endpoints


## Known Issues / Future Improvements
- The application currently uses an in-memory MySQL database. For production use, consider switching to a more robust database like MySQL or PostgreSQL.
- Add error handling and validation for user inputs and API responses.
- Implement pagination for listing endpoints that can potentially return large datasets.
- Improve error responses with clear error messages and HTTP status codes.


## Author
Your Name (@PappuLaL)