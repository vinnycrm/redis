# Redis in Docker Quick Setup
A quick setup for running Redis in Docker involves pulling the Redis image from Docker Hub and running a Redis container. Here’s a brief description:

1. **Pull the Redis Image**:  
   Run `docker pull redis` to fetch the latest Redis image from Docker Hub.

```sh
docker pull redis
```

2. **Run a Redis Container**:  
   Use the command `docker run --name my-redis -d redis` to start a Redis container named "my-redis" in detached mode.

```sh
docker run --name my-redis -d redis
```

3. **Access the Redis CLI**:  
   To interact with the Redis instance, execute `docker exec -it my-redis redis-cli`.

```sh
docker exec -it my-redis redis-cli
``` 

This setup provides a simple and isolated Redis environment, perfect for development and testing purposes.

## License

**The MIT License (MIT)**

Copyright © 2024 vinnycrm

## Community

Thanks to the people and companies who donate money, services or time to keep the project running.

[![text](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vinnycrm/) 
![X (formerly Twitter) URL](https://img.shields.io/twitter/url?url=https%3A%2F%2Fx.com%2Fvinnycrm)
