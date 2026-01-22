# Project 01: Jenkins Basic CI with Docker and Python

This project demonstrates a basic Continuous Integration (CI) pipeline using Jenkins, Docker, and Python.

The goal of this project is to understand how Jenkins pulls code from GitHub and builds a Docker image as part of a CI job.

---

## Project Overview

- Jenkins Freestyle job configured
- Source code pulled from GitHub repository
- Docker image built using Jenkins
- Python application containerized using Docker
- Jenkins integrated with Docker using Docker socket

---

## Technologies Used

- Jenkins
- Docker
- GitHub
- Python

---

## Project Structure

project-01-basic-ci  
├── Dockerfile  
├── app.py  
├── README.md  
└── screenshots  

---

## Jenkins Job Steps

1. Jenkins pulls the source code from GitHub
2. Jenkins runs a shell build step
3. Docker image is built using the Dockerfile
4. Build status is displayed in Jenkins console output

---

## Docker Build Command Used

```bash
docker build -t jenkins-python-ci .
