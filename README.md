# i2i Academy - Containerization & Analysis Project (Homework 2)

This repository contains the full solution for the Containerization and Analysis assignment. The project demonstrates how to package a web application inside a Docker container using Nginx and deploy it both in a local environment and on an AWS cloud server.

##  Project Structure
* `index.html` - The custom web page containing the styled deployment message.
* `docker-compose.yml` - Docker Compose configuration file handling port mapping (8080:80) and file volumes.
* `README.md` - Project documentation and setup guide.

##  How to Run Locally
1. Ensure Docker Desktop is installed and running on your machine.
2. Open your terminal/command prompt inside the project folder.
3. Execute the following command to start the container in detached mode:
   ```bash
   docker compose up -d
