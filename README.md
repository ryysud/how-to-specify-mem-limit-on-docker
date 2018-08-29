# how-to-specify-cpu-and-mem-limit-on-docker

```bash
# Compose file version 2
$ docker-compose -f docker-compose.ver2.yml up -d
$ docker stats --no-stream my-nginx

# Compose file version 3
$ docker-compose -f docker-compose.ver2.yml --compatibility up -d
$ docker stats --no-stream my-nginx
```