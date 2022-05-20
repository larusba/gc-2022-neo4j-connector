# Graph Connect 2022 - Master Real-Time Streams With Neo4j and Apache Kafka

## How to run

Be sure to have Docker installed and set Docker memory to a minimum of 4GB. 

<img width="1258" alt="Screenshot 2021-10-14 at 09 12 14" src="https://user-images.githubusercontent.com/12952543/137271680-50b39a2b-af68-4a7b-a839-fda9aea69f53.png">


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
