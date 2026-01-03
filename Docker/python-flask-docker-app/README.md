## Uploaded this in DockerHub website with name "python-flask-1" so that we can just pull and check output

# Simple Python Flask Dockerized Application#

## while doing practicals use below process

1. Launch and EC2 Instance and connect with git bash
2. sudo yum install git
3. git clone https://github.com/ThufelShaik-dev/Docker_files.git
4. cd python-flask-docker-app
5. ls -l # shows all files present here

6. Build the image using the following command
   $ docker build -t pyApp .

7. docker images

8.Run the Docker container using the command shown below.
$ docker run -d -p 5000:5000 pyApp

9. Add 5000 in security Inbound rules

10. The application will be accessible at http:EC2publicIp:5000
