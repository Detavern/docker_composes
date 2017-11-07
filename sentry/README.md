# README

```
docker-compose up -d
docker exec -it sentry bash, sentry upgrade
docker exec -it pip install sentry-slack
docker restart sentry
```