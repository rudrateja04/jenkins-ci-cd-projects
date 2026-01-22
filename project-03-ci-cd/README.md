# Project 03: Jenkins CI/CD Pipeline with Docker

This project demonstrates a complete CI/CD pipeline using Jenkins, Docker, GitHub, and Docker Hub.

The pipeline automates the process of building, pushing, and deploying a containerized application.

---

## Objective

- Implement end-to-end CI/CD using Jenkins Pipeline
- Build Docker image from source code
- Push Docker image to Docker Hub
- Deploy the application automatically using Docker

---

## Technologies Used

- Jenkins
- Docker
- Docker Hub
- GitHub
- Python (Flask)

---

## Project Structure

project-03-ci-cd  
├── app.py  
├── Dockerfile  
├── Jenkinsfile  
├── README.md  
└── screenshots  

---

## Application Overview

- `app.py` is a simple Flask web application
- The application exposes a basic HTTP endpoint
- Used to verify successful deployment

---

## CI/CD Pipeline Flow

1. Jenkins pulls source code from GitHub
2. Jenkins builds a Docker image using Dockerfile
3. Jenkins pushes the Docker image to Docker Hub
4. Jenkins deploys the application by running a Docker container
5. Application becomes accessible via browser

---

## Jenkinsfile Overview

The Jenkinsfile defines a declarative pipeline with stages for:
- Source code checkout
- Docker image build
- Docker image push to Docker Hub
- Application deployment using Docker

Pipeline configuration is fully version-controlled in GitHub.

---

## Deployment Verification

- Jenkins console output shows successful pipeline execution
- Docker Hub repository shows pushed image
- Application is accessible via browser on the configured port

---

## Key Learnings

- Jenkins Pipeline as Code
- CI vs CD concepts
- Secure credential handling in Jenkins
- Docker image lifecycle management
- Automated deployment using Jenkins

---

## Outcome

- Complete CI/CD pipeline implemented
- Application deployment is fully automated
- No manual steps required after code push

---

## Author

Rudra Teja
