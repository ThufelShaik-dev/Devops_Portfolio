# Dockerizing java web application i.e Pure java without spring boot

1. Launch an EC2 instance and connect with gitbash
2. sudo yum install maven
3. mvn -v
4. mvn archetype:generate -DgroupId=in.thufel -DartifactId=my-web-app -DarchetypeArtifactId=maven-archetype-webapp -DarchetypeVersion=1.0 -DinteractiveMode=false
5. ls -l #generate my-web-app
6. cd my-web-app
7. mvn clean package
8. vi Dockerfile # copy all commands present in this folder Dockerfile
9. docker build -t java-web-app .
10. docker images
11. docker run -d -p 8080:8080 java-web-app
12. make sure to add 8080 in security inbound rules
13. http://public-ip:8080/my-web-app
