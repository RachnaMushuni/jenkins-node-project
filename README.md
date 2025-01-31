# Jenkins-Docker-Node.js CI/CD Pipeline

This project demonstrates the implementation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline using Jenkins, Docker, and Node.js. The objective of this project is to automate the build and deployment process of a Node.js application using Jenkins to trigger Docker container creation. It also showcases best practices for automating the deployment process and streamlining the development lifecycle.

## Tools and Technologies Used:
- **Jenkins**: For automating the build, test, and deployment processes.
- **Docker**: For containerizing the Node.js application to ensure a consistent development and production environment.
- **Node.js**: The backend application being containerized and deployed.
- **Ubuntu**: Operating system used to run the application and Jenkins server.
- **GitHub**: Version control and repository hosting platform for the project.
- **Docker Compose** (optional if you plan to use): For defining and running multi-container Docker applications.

## Project Setup Instructions:

1. **Clone the Repository**:
   - Open your terminal and clone this repository to your local machine:
     ```bash
     git clone https://github.com/YourUsername/jenkins-node-project.git
     ```
     Replace `YourUsername` with your actual GitHub username.

2. **Install Docker and Jenkins**:
   - Ensure Docker is installed on your machine:
     - [Install Docker](https://docs.docker.com/get-docker/)
   - Install Jenkins if it's not installed:
     - [Install Jenkins](https://www.jenkins.io/doc/book/installing/)
   
3. **Jenkins Setup**:
   - Set up Jenkins to build the Docker container for the Node.js application.
   - Use the provided Jenkins pipeline script (Jenkinsfile) to configure the pipeline.

4. **Run the Pipeline**:
   - Once Jenkins is set up, run the pipeline to build the Docker image and deploy the container.

5. **Access the Application**:
   - The Node.js application will be accessible via `http://localhost:3000/` after the pipeline runs successfully.

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
![Application Running on Jenkins]([link-to-screenshot.png](https://github.com/RachnaMushuni/jenkins-node-project/blob/master/Screenshot%20from%202025-02-01%2004-24-07.png))

![Application Running on Server]([link-to-screenshot.png](https://github.com/RachnaMushuni/jenkins-node-project/blob/master/Screenshot%20from%202025-02-01%2004-24-07.png)](https://github.com/RachnaMushuni/jenkins-node-project/blob/master/Screenshot%20from%202025-02-01%2004-25-54.png))

## Future Improvements:
- **Add Automated Testing**: Integrate automated tests within the pipeline to ensure code quality.
- **Cloud Deployment**: Set up deployment on cloud platforms like AWS, Azure, or GCP.
- **Enhanced Monitoring**: Implement monitoring tools (like Prometheus) to monitor the deployed application in real-time.

## Why This Project?
This project aims to showcase the use of CI/CD practices using Jenkins and Docker. It automates the process of building, testing, and deploying applications, making it easier to manage and update software deployments in production environments. By using Docker containers, the application can be deployed consistently across various environments, ensuring that it works seamlessly across development, staging, and production.

This project is highly relevant for DevOps roles and demonstrates the ability to work with modern DevOps tools and methodologies, making it a strong addition to your portfolio.
