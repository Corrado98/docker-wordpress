# docker-wordpress
Lightweight docker-compose wordpress setup with phpmyadmin for database administration.

## requirements:
- docker installation on os.
- docker shared drive for volumes (windows-specific).

![docker-shared-drives](https://itsananderson.blob.core.windows.net/post-images/docker-shared-drives.png)

## usage:
Within the ```docker-compose.yaml``` file location open a terminal and run the command:
```docker-compose up```.

A ```wordpress``` and ```db``` folder will be created which are bidirectional mounts from the corresponsing containers to your host filesystem.

## urls:
wordpress: http://localhost:8080
phpmyadmin: http://localhost:8082

