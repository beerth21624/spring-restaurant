# Restaurant API

This project is a Spring Boot application that provides a RESTful API for managing restaurant information.

## Developer
- Sarawut Inpol (6510405822)

## Overview

The Restaurant API allows users to perform CRUD (Create, Read, Update, Delete) operations on restaurant data. It includes functionality to manage restaurant details such as name, rating, and location.

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- H2 Database

## Setup Instructions

1. Clone the repository:
   ```
   git clone https://github.com/beerth21624/spring-restaurant.git
   ```

2. Navigate to the project directory:
   ```
   cd restaurant-api
   ```

3. Build the project:
   ```
   ./mvnw clean install
   ```

4. Run the application:
   ```
   ./mvnw spring-boot:run
   ```

The API will be available at `http://localhost:8080`.

## API Endpoints

- GET `/restaurant`: Retrieve all restaurants
- POST `/restaurant`: Create a new restaurant
- GET `/restaurant/{id}`: Retrieve a specific restaurant by ID
- PUT `/restaurant`: Update an existing restaurant
- DELETE `/restaurant/{id}`: Delete a restaurant
- GET `/restaurant/name/{name}`: Retrieve a restaurant by name
- GET `/restaurant/location/{location}`: Retrieve restaurants by location

## Data Model

The `Restaurant` entity includes the following fields:
- `id` (UUID): Unique identifier for the restaurant
- `name` (String): Name of the restaurant
- `rating` (double): Rating of the restaurant
- `location` (String): Location of the restaurant

## Testing

You can use the provided Postman collection to test the API endpoints. Import the collection into Postman and update the variables as needed.

## Contributing

If you'd like to contribute to this project, please fork the repository and create a pull request with your changes.

## License

[Specify your license here, e.g., MIT, Apache 2.0, etc.]