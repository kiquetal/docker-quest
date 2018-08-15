### Steps to install docker

Install docker 

##### yum install docker

Create user

#### groupadd docker

Add user to the group

#### usermod -aG docker cloud_user

 Enable service

#### systemctl enable --now docker

Check docker

#### docker ps

Install image for docker

#### docker pull docker.io/hello-world

Run image

#### docker run hello-world

Running static web pages

#### docker run -d --name treatseekers -p 80:80 spacebones/doge

