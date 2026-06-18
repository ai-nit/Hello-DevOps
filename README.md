# Hello-DevOps
# DevOps CI/CD Pipeline Project

## Project Overview

This project demonstrates a simple Python Flask application integrated with DevOps practices including Docker containerization and GitHub Actions CI automation.

The pipeline automatically validates the application and builds a Docker image whenever code is pushed to the main branch or a pull request is created.

---

## Tools Used

* Python 3.11
* Flask
* Docker
* GitHub Actions
* Git

---

## How to Run Locally

### Clone the Repository

```bash
git clone <repository-url>
cd <repository-name>
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

The application will start on:

```text
http://localhost:5000
```

---

## How to Build the Docker Image

Build the Docker image:

```bash
docker build -t hello-devops-app .
```

Run the container:

```bash
docker run -p 5000:5000 hello-devops-app
```

Open:

```text
http://localhost:5000
```

---

## GitHub Actions Workflow

The GitHub Actions workflow automatically:

1. Checks out source code.
2. Sets up Python 3.11.
3. Installs dependencies.
4. Validates the application.
5. Builds the Docker image.

---

## GitHub Actions Success Screenshot

Add a screenshot of a successful workflow run here.

Example:

![GitHub Actions Success](images/github-actions-success.png)

---

## What I Learned

Through this project, I learned:

* Creating a Flask application.
* Managing project dependencies using requirements.txt.
* Containerizing applications with Docker.
* Automating builds using GitHub Actions.
* Implementing Continuous Integration (CI) workflows.
* Using Git and GitHub for version control and collaboration.

---

## Author

Baburao Patil
