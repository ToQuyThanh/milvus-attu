# Milvus-Attu

This repository is for storing code to deploy, manage, and use the Milvus database.

## Deploy Milvus using Docker Compose
To start Milvus using Docker Compose, run the following command in your terminal:

```sh
docker-compose up -d
```

The Milvus API can be accessed through the following ports:
- [http://localhost:19530](http://localhost:19530)for the Milvus service
- [http://localhost:9091](http://localhost:9091) for the Milvus web interface


Attu can be accessed through the following port:
- [http://localhost:8000](http://localhost:8000) for the Attu web interface

Minio can be accessed through the following ports:
- [http://localhost:9001](http://localhost:9001) for the Minio console
- [http://localhost:9000](http://localhost:9000) for the Minio service

