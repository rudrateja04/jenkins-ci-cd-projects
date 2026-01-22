# Project 02: Jenkins Pipeline using Jenkinsfile

This project demonstrates a Jenkins Continuous Integration (CI) pipeline implemented using a Jenkinsfile (Pipeline as Code).

The objective of this project is to move from Jenkins Freestyle jobs to a version-controlled Jenkins pipeline stored in GitHub.

---

## Project Overview

- Jenkins pipeline created using Jenkinsfile
- Pipeline configuration stored in GitHub
- Docker image built using Jenkins pipeline
- Python application executed inside Docker container
- No Jenkins UI-based build configuration

---

## Technologies Used

- Jenkins
- Docker
- GitHub
- Python

---

## Project Structure

project-02-jenkins-pipeline  
├── Dockerfile  
├── app.py  
├── Jenkinsfile  
├── README.md  
└── screenshots  

---

## Application Description

- `app.py` is a simple Python application
- Dockerfile containerizes the Python application
- Jenkinsfile defines the CI pipeline stages

---

## Jenkinsfile Overview

The Jenkinsfile defines a declarative pipeline with stages for:
- Building a Docker image
- Running the Docker container

This enables Pipeline as Code and removes dependency on Jenkins UI configuration.

---

## CI Pipeline Flow

1. Jenkins pulls source code from GitHub
2. Jenkins reads Jenkinsfile from the repository
3. Docker image is built inside the pipeline
4. Docker container is executed
5. Pipeline completes successfully

---

## Key Learnings

- Jenkins Pipeline as Code (Jenkinsfile)
- Declarative pipeline syntax
- Using stages in Jenkins pipeline
- Running Docker commands from Jenkins pipeline
- Difference between Freestyle jobs and Pipelines

---

## Outcome

- Jenkins pipeline runs successfully
- Docker image is built and executed through Jenkinsfile
- CI process is fully version-controlled in GitHub

---

## Author

Rudra Teja
