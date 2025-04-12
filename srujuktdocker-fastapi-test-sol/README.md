# sol-dockerized-fastapi-test
This project shows how to Dockerize a FastAPI application that performs basic operations like adding and retrieving users, without relying on a traditional database. Instead, user data is stored in a users.json file.
 The application is divided into separate files for the core API logic (main.py), data handling (services.py), and data models (schema.py), all within an app directory. The user data is kept in a data folder.
  The project includes a Dockerfile to create a container for the application, and a docker-compose.yml file to manage the container, including mounting a volume to keep the users.json file on the host system. 
  This setup ensures that the data remains intact even if the container is removed and recreated.