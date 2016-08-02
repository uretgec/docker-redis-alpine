# docker-redis-alpine
Redis Alpine Dockerfile

# Usage
- redis.conf file copy into "docker_volume_name" folder.
- Download redis.conf file: http://download.redis.io/redis-stable/redis.conf

```
$ docker run -d --name docker_redis_alpine -v <docker_volume_name>:/data uretgec/docker-redis-alpine
```

# Many many Thanks
https://github.com/docker-library/redis
