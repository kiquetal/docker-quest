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

