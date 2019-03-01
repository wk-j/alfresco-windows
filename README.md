## Windows

```bash
docker-compose down
docker-compose up
```

## Volume

```
docker volume create alfresco-data
docker volume create postgresql-data
docker volume create solr-data
```

## Inspect

```
docker volume inspect alfresco-data
docker volume inspect postgresql-data
docker volume inspect solr-data
```

## Exec

```
docker exec -it alfrescowindows_alfresco_1 bash
docker exec -it alfrescowindows_postgres_1 bash
docker exec -it alfrescowindows_solr6_1 bash
```

## Copy config


```
docker exec -it alfrescowindows_alfresco_1 sh -c 'cat shared/classes/alfresco-global.properties'
docker-compose exec alfresco sh -c 'pwd'
docker cp alfrescowindows_alfresco_1:/usr/local/tomcat/shared/classes/alfresco-global.properties config
```