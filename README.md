```bash
ssh -i "ekomobong.pem" ubuntu@ec2-54-234-55-118.compute-1.amazonaws.com
```

```bash
# Create the `docker-compose.yaml` for traefik (traefik-demo-1/docker-compose.yaml)
```

```bash
# Check network
docker network ls

# Create docker network
docker network create frontend
```

```bash
# Create the `traefik.yaml` (traefik-demo-1/config/traefik.yaml)
```

```bash
# Start the traefik reverse proxy
# by executing the docker compose file
# in directory `traefik-demo-1`
docker compose up
docker compose up -d # (background)
```

```bash
# Create the `docker-compose.yaml` for nginx (nginx-demo-1/docker-compose.yaml)

# Start the container
docker compose up -d
```

```bash
# Check logs
docker compose logs -f
```
