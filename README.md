This repository contains the necessary files and scripts to set up an Nginx web server using Docker. 
The setup allows you to run Nginx seamlessly in your browser, demonstrating containerization and web server management.

Before you begin, ensure you have the following installed:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/)

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/nginx-docker-setup.git
   cd nginx-docker-setup

2. Build the Docker image:

   docker build -t nginx-image .

3. Running the Application

   docker run -d -p 9000:80 nginx-image

Accessing Nginx

  http://localhost:9000/