# Task-4-Abdelrahman-Hamdy-Saied-Glall
# DevOps Project 4 - Containerization with Docker

## Objective

Learn the basics of Docker by containerizing a simple Python Flask application.

## Project Structure

```text
devops-project4/
│
├── app.py
├── requirements.txt
├── Dockerfile
└── README.md
```

## Technologies Used

- Docker
- Python
- Flask

## Docker Commands

### Build Image

```bash
docker build -t flask-app .
```

### Run Container

```bash
docker run -p 5000:5000 flask-app
```

## Expected Output

Open:

http://localhost:5000

You should see:

Hello from Docker!

## Skills Practiced

- Docker Basics
- Containerization
- Building Images
- Running Containers
- Application Packaging
