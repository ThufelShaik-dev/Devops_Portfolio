## uploaded this in DockerHub with name as "node-app-1" so that we can pull and check output

# Dockerizing node application

1. Launch an EC2 instance and connect with gitbash
2. sudo yum install git
3. git -v
4. git clone https://github.com/ThufelShaik-dev/Docker_files.git
5. ls -l # shows all files present in this repo
6. cd node-app/node-app
7. docker build -t node-app-1 .
8. docker images
9. docker run -d -p 3000:8000 --name node-app--container node-app-1
10. make sure to add 3000 in security inbound rules
11. http://public-ip:3000
