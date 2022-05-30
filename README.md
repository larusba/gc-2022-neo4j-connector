# Graph Connect 2022 - Master Real-Time Streams With Neo4j and Apache Kafka

## How to run

Be sure to have Docker installed and set Docker memory to a minimum of 8GB. 

<img width="934" alt="Screenshot 2021-10-21 at 15 30 29" src="https://user-images.githubusercontent.com/12952543/138288132-d2922cc2-12ea-40c4-9e3a-a0b33ef3406c.png">


In order to prevent conflicts with existent Docker containers i suggest to stop all your running containers with the following:

```
docker stop $(docker ps -a -q)
```

Then run the following command from the repository root directory:

```
docker-compose up -d
```

It will take some time to download all the Docker images. 

Once it's started please visit [localhost:8080](http://localhost:8080) to view the Zeppelin interface and start playing with the notebook!
