# PythonRestAPIProject
## Build Docker image 
```commandline
docker build -t python-rest-api .
```

## Run Docker image
```commandline
docker run -p 9001:9001 python-rest-api
```

## Build and tag according to DockerHub
```bash
docker tag python-project farahbhr/python-rest-api:1.0
```

## Docker push
```bash
docker push farahbhr/python-rest-api:1.0
```