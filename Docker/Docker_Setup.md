## Setup Linux VM (Amazon Linux / Ubuntu)

1. Login into AWS Cloud account
2. Create Linux VM and connect to it using Gitbash/MobaXterm

## Install Docker In Amazon Linux VM

```
### Update existing packages
sudo yum update -y

### Install Docker
sudo yum install docker -y

### Start Docker service
sudo service docker start

### Add ec2-user to Docker group
sudo usermod -aG docker ec2-user

### Logout and login again to apply group changes
exit
```

## Install Docker In Ubuntu VM

```
sudo apt update
curl -fsSL get.docker.com | /bin/bash
sudo usermod -aG docker ubuntu
exit
```

## Verify docker installation

```
docker -v
```
