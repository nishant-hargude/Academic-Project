# Online Hospital Management System

The Online Hospital Management System is a web application designed to facilitate the management of hospital resources, 
appointments, and patient records. The project is built using a microservices architecture, with the backend implemented 
in Spring Boot, and the frontend developed using ReactJS.

## Microservices Architecture

The application is divided into four microservices:

1. **Hms_apis**: This microservice handles hospital-related functionalities, such as managing appointments, doctors, patients, 
and medical records. It is built using Spring Boot and uses MySQL as its database.

2. **Resources_apis**: This microservice is responsible for managing hospital resources, such as medical equipment, rooms, and 
supplies. It is built using Spring Boot and uses MongoDB as its database.

3. **Eureka Server**: This is the service registry server, which helps in discovering and connecting to different microservices.

4. **API Gateway**: The API Gateway acts as an entry point for the frontend application to interact with the backend microservices. 
It routes the requests to the appropriate microservices.

## Technologies Used

- Backend: Spring Boot, Spring Cloud, MySQL, MongoDB
- Frontend: ReactJS

## Installation and Setup

1. Clone the repository from GitHub:
git clone https://github.com/nishant-hargude/Academic-Project.git


2. Backend Setup:
- Navigate to each of the four microservices folders (Hms_apis, Resources_apis, Eureka Server, and API Gateway) in the terminal.
- For Hms_apis and Resources_apis, make sure you have MySQL and MongoDB installed and running. Update the database configurations in 
`application.properties` files accordingly.
- Run the Spring Boot applications using the following command in each microservice folder:

  ```
  ./mvnw spring-boot:run
  ```

3. Frontend Setup:
- Navigate to the `frontend` folder in the terminal.
- Install the required dependencies using:

  ```
  npm install
  ```

- Start the ReactJS development server:

  ```
  npm start
  ```

The application will be accessible at `http://localhost:3000`.

## Contributing

Contributions to the Online Hospital Management System are welcome. 
If you find any issues or want to add new features, please create a pull request.


## Contact

For any questions or inquiries, please contact me at your-hargudenishant@gmail.com.


