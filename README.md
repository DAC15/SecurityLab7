# MongoDB Encryption and Decryption with Spring Boot

This is a simple Spring Boot POC to use MongoDB cascading features provided by Spring Boot, I encrypt data before saving to MongoDB and decrypting it after fetching from MongoDB.

## Configuration

Change MongoDB connection configuration in the ```resources/application.properties``` file. The property is ```spring.data.mongodb.uri```. An example:

