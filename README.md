# Docker Container Name

Transcibtion inference api container image. For running on gcp cloud run  

#### Run locally  

To test the api or run locally do: 

```shell
docker build -t <image name> .
```

then: 

```shell
docker run -p 8000:8000 <image name>
```

## Built With

* OpenAi Whisper v1.0.0
* Uvicorn v0.15.0
* FastApi 0.85.1



* [GitHub](https://github.com/Hetling)
* [Dockerhub](https://hub.docker.com/repository/docker/hetling/asr-v2)