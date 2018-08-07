# Apache Mod Study

## install

```
docker-compose build
docker-compose up
```

```
docker-compose run --rm httpd /usr/sbin/apxs -g -n hello_world
docker-compose run --rm httpd /usr/sbin/apxs -i -a -c hello_world/mod_hello_world.c
```