## Windows

```bash
docker-compose down
docker-compose up


docker volume create alfresco-data
docker volume create postgresql-data
docker volume create solr-data

docker volume inspect alfresco-data
docker volume inspect postgresql-data
docker volume inspect solr-data


docker exec -it alfrescowindows_alfresco_1 bash
docker exec -it alfrescowindows_postgres_1 bash
docker exec -it alfrescowindows_solr6_1 bash

```