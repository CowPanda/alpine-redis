### alpine-redis
alpine redis 

> This redis instance require auth default (_password:`redis`_) . your can assign your redis.conf use `--volume` customize redis password 
> or cluster config.

###usage

    docker run -d --name redis -v your_redis_conf_path:/usr/local/etc/redis/redis.conf -p 6379:6379 cowpanda/alpine-redis:latest

