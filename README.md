# code base for simple example of microservices
Steps to run this project:

Clone this Git repository

Navigate to the folder microservices

Build the application with mvn clean package

Start you Docker deamon

Build the Docker image with docker build -t microservices .

Start the Docker container with docker run -p 8080:8080 --name microservices microservices

Wait until the Payara server is launched successfully and visit http://localhost:8080/microservices-1.0-SNAPSHOT/webresources/hello to view the running JAX-RS sample code
