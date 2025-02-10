# Jenkins-Docker-Node.js CI/CD Pipeline

This project demonstrates the implementation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline using Jenkins, Docker, and Node.js. The objective of this project is to automate the build and deployment process of a Node.js application using Jenkins to trigger Docker container creation. It also showcases best practices for automating the deployment process and streamlining the development lifecycle.

## Tools and Technologies Used:
- **Jenkins**: For automating the build, test, and deployment processes.
- **Docker**: For containerizing the Node.js application to ensure a consistent development and production environment.
- **Node.js**: The backend application being containerized and deployed.
- **Ubuntu**: Operating system used to run the application and Jenkins server.
- **GitHub**: Version control and repository hosting platform for the project.
- **Docker Compose**: For defining and running multi-container Docker applications.

## How the Project Works:

1. **Build Process**:
   - Jenkins triggers the build process whenever there is a change in the GitHub repository.
   - It runs the Docker build command to create an image of the Node.js application.

2. **Deployment**:
   - After the Docker image is built, Jenkins deploys the image to a Docker container.
   - The application is now accessible via `http://localhost:3000/`.

3. **Jenkins Automation**:
   - Jenkins handles the automation of the entire process, ensuring that changes are automatically built and deployed.

## Screenshots:
![Application Running on Jenkins](https://github.com/RachnaMushuni/jenkins-node-project/blob/master/Screenshot%20from%202025-02-01%2004-24-07.png)

![Application Running on Server](https://github.com/RachnaMushuni/jenkins-node-project/blob/master/Screenshot%20from%202025-02-01%2004-25-54.png)

## Why This Project?
This project aims to showcase the use of CI/CD practices using Jenkins and Docker. It automates the process of building, testing, and deploying applications, making it easier to manage and update software deployments in production environments. By using Docker containers, the application can be deployed consistently across various environments, ensuring that it works seamlessly across development, staging, and production.
