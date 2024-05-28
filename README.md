# Flask Application Template

This simple Flask application template for building web applications using Flask, a popular Python web framework.

## Features

- Serve HTML templates with Flask.
- Handle static files (CSS, JavaScript, images) using Flask's built-in static file handling.
- Dockerized for easy deployment and portability.

## Directory Structure

flask-app/
├── app.py # Flask application code
├── Dockerfile # Dockerfile for building the Docker image
├── requirements.txt # List of Python dependencies
├── templates/ # HTML templates directory
│ └── index.html # Main HTML template
└── static/ # Static files directory
└── image/ # Directory for image files
└── your_image.jpg # Example image file


## Usage

1. Clone the repository:
  
   git clone https://github.com/viktor134/First_docker_container

2. Navigate to the project directory:
   cd flask-app

3. Build the Docker image:
  docker build -t flask-app .

4 Run the Docker container:
  docker run -p 80:80 flask-app
  
5 Access the application in your web browser at http://localhost:80/.

License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

Flask - https://flask.palletsprojects.com/
Docker - https://www.docker.com/
