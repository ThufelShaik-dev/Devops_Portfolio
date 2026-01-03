## Uploaded this in DockerHub website with name "java-web-app-2"

## while doing practicals use below process

1. Launch and EC2 Instance and connect with git bash 
2. sudo yum install git
3. git clone -this git repo URL-
4. cd maven-web-app
5. mvn clean package
6. docker build -t maven-web-app .
7. docker images
8. docker run -d -p 8080:8080 maven-web-app
9. Add 8080 in security Inbound rules
10. http://public-ip:8080/maven-web-app 
