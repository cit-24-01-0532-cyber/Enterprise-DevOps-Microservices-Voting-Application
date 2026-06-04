# 🛸 Enterprise DevOps & Microservices Voting Application

An interactive, high-performance **Cats vs Dogs Voting Application** deployed on an **AWS EC2 Instance** using Docker and production-ready DevOps methodologies.

## 🚀 Project Architecture
The frontend is built using **Python (Flask)** which containerizes the user interface and serves incoming requests. It captures user votes and renders the dynamic container hostname/ID from the AWS cloud infrastructure.

## 🛠️ Tech Stack & Concepts Covered
- **Backend/Frontend:** Python (Flask), HTML5, CSS3 (Premium Dark Theme)
- **Containerization:** Docker & Docker Desktop
- **Cloud Infrastructure:** AWS EC2 Virtual Machine
- **DevOps Principles:** Port-forwarding, container isolation, environment variable injection

## 📁 Repository Structure
- `app.py`: Core Python Flask application logic.
- `templates/index.html`: Premium dark-themed UI frontend.
- `Dockerfile`: Multi-stage build configuration for lightweight image production.

- ##Screenshorts
- https://github.com/cit-24-01-0532-cyber/Enterprise-DevOps-Microservices-Voting-Application/blob/main/Screenshot%202026-05-28%20102744.png
- https://github.com/cit-24-01-0532-cyber/Enterprise-DevOps-Microservices-Voting-Application/blob/main/Screenshot%202026-05-28%20102750.png
- https://github.com/cit-24-01-0532-cyber/Enterprise-DevOps-Microservices-Voting-Application/blob/main/Screenshot%202026-06-04%20131840.png
https://github.com/cit-24-01-0532-cyber/Enterprise-DevOps-Microservices-Voting-Application/blob/main/Screenshot%202026-06-04%20131828.png
- 

## 📦 Local Deployment (Docker)
To run this project locally, execute the following commands:

```bash
# 1. Build the Docker image
docker build -t voting-app-frontend ./app

# 2. Run the container on port 5000
docker run -d -p 5000:5000 --name voting-front voting-app-frontend
