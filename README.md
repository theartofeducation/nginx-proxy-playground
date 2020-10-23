# Nginx Playground

Using Nginx as a reverse proxy for local development

## Usage

You will need to have docker installed.

https://docs.docker.com/get-docker/


```bash
docker pull nginx
```
To pull the latest nginx image


```bash
docker-compose up
```
to run the proxy and sample services. It will be available at `localhost:3000`

`/` or `/pro` will redirect to the `pro-service` running in docker
`/flex` will redirect to the `flex-service` running in docker