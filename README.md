## Windows

```bash
docker-compose down
docker-compose up

docker exec -it alfrescowindows_alfresco_1 bash
docker exec -it alfrescowindows_postgres_1 bash

docker volume inspect  alfrescowindows_alfresco-data
docker volume inspect  alfrescowindows_postgresql-data
```