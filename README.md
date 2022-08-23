# Docker-Compose
By using this template you can write a single docker-compose file to run multiple containers

### What is Docker Compose?

Docker Compose is used for running multiple containers as a single service. Each of the containers here run in isolation but can interact with each other when required. Docker Compose files are very easy to write in a scripting language called YAML, which is an XML-based language. Another great thing about Docker Compose is that users can activate all the services (containers) using a single command.

In this template, four services are running i.e. server, zookeeper, producer and consumer

### To run the docker-compose file type

`docker-compose up --build`

### Run producer in other terminal to enter messages, type command

`docker-compose run producer`

In producer terminal type message `HELLO`

In consumer terminal you see message `HELLO`
