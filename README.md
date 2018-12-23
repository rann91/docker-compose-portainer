Customized Docker Compose template for [Portainer](https://www.portainer.io/). This template is meant to be used with [nginx-proxy](https://github.com/jwilder/nginx-proxy). Use my [nginx-proxy template](https://github.com/rann91/docker-compose-nginx-proxy) to setup nginx proxy quickly.

## Usage
Copy default .env file to set virtual host and letsencrypt configuration. Then simply run docker-compose:
```
docker-compose up -d
```

That's it!
