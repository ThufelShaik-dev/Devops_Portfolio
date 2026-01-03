# Simple Spring Boot with Docker Application#

## Uploaded this in DockerHub website with name "java-spring-1" so that we can just pull and check output

## while doing practicals use below process

1. Launch and EC2 Instance and connect with git bash
2. sudo yum install git
3. git clone https://github.com/ThufelShaik-dev/Docker_files.git
4. cd spring-boot-docker-app
5. mvn clean package
6. ls -l target # verify whether jar file generated or not
7. Build the image using the following command
   docker build -t sb-app .

8. docker images

9. Run the Docker container using the command shown below.
   docker run -d -p sb-app

10. Add 8080 in security Inbound rules
11. The application will be accessible at http://EC2-publicIP:8080/
