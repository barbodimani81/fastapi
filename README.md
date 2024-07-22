# FastAPI Docker Project

This is a simple FastAPI application with Docker setup. The application includes a few basic endpoints to demonstrate FastAPI's capabilities.

## Table of Contents

- [Project Description](#project-description)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Docker Setup](#docker-setup)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Project Description

This project is a basic FastAPI application that demonstrates how to create a RESTful API with Docker. The API includes two endpoints:
- `/` - Returns a "Hello World" message.
- `/hello/{name}` - Returns a personalized greeting message.

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:
- [Docker](https://www.docker.com/)
- [Python 3.9+](https://www.python.org/)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/barbodimani81/fastapi.git
    cd your-repo
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the FastAPI application locally without Docker, use the following command:
```bash
uvicorn app.main:app --reload
