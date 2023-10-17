# nginx-load-balancer-docker

## Start the containers
```bash
docker-compose up -d
```

## Utils
To see the access logs on each node:
```bash
tail -f /var/log/nginx/host.access.log
```
