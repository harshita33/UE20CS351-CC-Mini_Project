# Microservice communication with RabbitMQ

Building and deploying a microservices architecture where multiple components communicate with each other using RabbitMQ. A message broker is an architectural pattern for message validation, transformation and routing. For the scope of this project, we build 4 microservices: A HTTP server that handles incoming requests to perform CRUD operations on a Student Management Database , Check the health of the RabbitMQ connection, a microservice that acts as the health check endpoint, a microservice that inserts a single student record, a microservice that retrieves student records, a microservice that deletes a student record given the SRN.

