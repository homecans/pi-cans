# issue
## nignx
- [x] missing /run/nginx 
- [] update/push docker image to hub 

## php
- [x] www-data user
- [x] CMD ["nginx", "-g", "daemon off;"]  ["/usr/sbin/php-fpm7", "-F", "-R"]
- [] update/push docker image to hub



# todo
## nignx
- [] update/push docker image to hub 

## php
- [] update/push docker image to hub


## add back db
```
    mariadb:
        image: coincan/mariadb
        container_name: pi-cans-mariadb
        restart: on-failure
        volumes:
          - ./database:/var/lib/mysql
        ports:
          - 13306:3306
        expose:
          - 6379
```