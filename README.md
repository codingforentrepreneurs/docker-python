# Docker Python
Dockerfiles for various python configurations. View this on Dockerhub at [codingforentrepreneurs/python](https://hub.docker.com/repository/docker/codingforentrepreneurs/python).




## Using our pre-built images:
Our long term goal is to have images that make it more effecient to bootup a docker-based python application. See ways to improve? Please submit a pull request.



### Python 3.9 Webapp wuth Selenium & Chromedriver

```Dockerfile
FROM codingforentrepreneurs/python:3.9-webapp-selenium
```

### Python 3.9 Webapp with Chromedriver (no selenium)

```Dockerfile
FROM codingforentrepreneurs/python:3.9-webapp-chromedriver
```


### Python 3.9 Webapp Slim

```Dockerfile
FROM codingforentrepreneurs/python:3.9-webapp-slim
```

### Python 3.9 Webapp with Cassandra Driver

```Dockerfile
FROM codingforentrepreneurs/python:3.9-webapp-cassandra
```

### Python 3.9 Webapp with Cassandra Driver & Selenium

```Dockerfile
FROM codingforentrepreneurs/python:3.9-webapp-cassandra-selenium
```
