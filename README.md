# Current Date/Time API - Python/Go Project
This project provides a simple API endpoint that returns the current date and time.

Features
API Endpoint: /current-time - Returns the current date and time in YYYY-MM-DD HH:MM:SS format.

Dockerized: The application is containerized using Docker for easy deployment and portability.

Getting Started
Prerequisites
Docker installed on your system.

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/baig892/task1.git
Build the Docker image:

bash
Copy
Edit
docker build -t current-time-api .
Run the container:

bash
Copy
Edit
docker run -p 5000:5000 current-time-api
Visit http://localhost:5000/current-time in your browser to see the current date and time.
