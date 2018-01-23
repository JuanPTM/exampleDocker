# exampleDocker
Example Docker-Compose several docker-compose (currently problem: https://github.com/docker/compose/issues/3874)

# Execute
```bash
docker-compose -f docker-compose.yml -f foo/docker-compose.yml -f bar/docker-compose.yml up -d

```

# Stop

```
docker-compose -f docker-compose.yml -f foo/docker-compose.yml -f bar/docker-compose.yml down
```
