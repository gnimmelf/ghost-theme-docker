# ghost-theme-docker
Boilerplate repository for Ghost theme development with Docker.  
More information at <https://rishabhmhjn.com/ghost-theme-development-environment-with-docker>

## Development

```bash
docker-compose -f "docker-compose.yml" up -d --build
```

Now you can open your newly set up Ghost blog at <http://localhost:3102/>

## Debugging

Get container id
```
sudo docker ps
```

Start "interactive" bash session
```
sudo docker exec -it <CONTAINER_ID> /bin/bash
```
