Building the docker base images
===============================

cd centos-latest
docker build -t 'abadger/ansible:centos7-ansible1.8-v2'  .

cd ubuntu-lts-latest
docker build -t 'abadger/ansible:ubuntu14.04-ansible1.8-v2'  .

Example of using the Docker images with an ansible playbook
===========================================================

pending