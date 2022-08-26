# Docker-Compose
By using this template you can write a single docker-compose file to run multiple containers

In this template, four services are running i.e. **kafka server, zookeeper, producer and consumer**

### To run the docker-compose file type

`docker-compose up --build`

### Run producer in other terminal to enter messages, type command

`docker-compose run producer`

In producer terminal type message `HELLO`

In consumer terminal you see message `HELLO`

### Like this

![Screenshot from 2022-08-23 19-16-44](https://user-images.githubusercontent.com/94070460/186175528-abea8969-aa39-4dd9-bcef-dd093a96db5f.png)

![Screenshot from 2022-08-23 19-16-49](https://user-images.githubusercontent.com/94070460/186175804-825fd77f-1296-4a10-a1d9-883965184bfe.png)

For more information refer - https://blog.knoldus.com/how-to-solve-producer-and-consumer-problems/
