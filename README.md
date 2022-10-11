# Shlink Server/Web-Client/MySQL

## Installation
### create .env
```
GEOLITE_LICENSE_KEY=put_your_licence_key_here
```
### Run Docker
```bash
docker-compose up -d
```

### Generate API Key
```bash
docker exec -it shlink_server shlink api-key:generate
```

### Open in Browser
- Shlink Server: [localhost:8080](http://localhost:8080)
- Shlink Web-Client: [localhost:8081](http://localhost:8081)

## Docker Images
- [shlinkio/shlink:stable](https://hub.docker.com/r/shlinkio/shlink)
- [shlinkio/shlink-web-client](https://hub.docker.com/r/shlinkio/shlink-web-client)
- [mysql:5.7](https://hub.docker.com/_/mysql)

## GeoLite Licence Key
visit: https://www.maxmind.com/en/accounts/<your-account-id>/license-key


