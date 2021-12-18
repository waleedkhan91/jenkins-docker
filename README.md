# jenkins-docker
Jenkins CI with Docker client

   To find the group of docker to be entered in line 9 of Dockerfile, use following command.
> cat /etc/group | grep docker
OR
> getent group docker

   Please note that this demonstration is tested on CentOS8 as basic OS and Docker v 19.03.15 CE.