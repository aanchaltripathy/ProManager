# ProManager
Built a robust Java-based CRUD API using Spring Boot, MySQL, and Docker to manage store data with seamless containerized deployment. The project involved creating a RESTful API that handles Create, Read, Update, and Delete operations while ensuring scalability and smooth database management.

### Technologies Used:
- Java
- Spring Boot
- MySQL
- Docker & Docker Compose
- REST API
- Environment Variables for Configuration


 #### Steps
- Developed a Java-based REST API with Spring Boot to manage store-related data
- Testing the health("/health) path




![postmancheck](https://github.com/user-attachments/assets/14b2c859-5ef6-456b-aca0-0b42194efcff)

- Adding products using POST method on POSTMAN




![updateprod](https://github.com/user-attachments/assets/0ecf597b-9167-4a9e-b4b4-7fda436e6fcc)


- Check the database










![database](https://github.com/user-attachments/assets/68a7f4a5-f92a-4911-b658-a87402dee985)










 








- Dockerized the application by creating separate Dockerfiles for both the API and MySQL, ensuring consistent and isolated environments for development and production.
- Implemented Docker Compose to run and manage both the MySQL container and Java application container, simplifying deployment and orchestration.
- Configured the application.properties to connect the Java API to the MySQL database container.
- SHOW TABLES to view the product_inventory table created earlier









![prodinventtable](https://github.com/user-attachments/assets/91a307c8-8851-4610-843f-fb8fee56a933)

- Items in the table





![items](https://github.com/user-attachments/assets/87adae87-93e2-46ea-a338-5f04f3e60bf9)






- Conducted health checks and tested the API using curl to verify the functionality of all CRUD operations.
