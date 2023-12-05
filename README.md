# Docker Container Monitoring with cAdvisor, Prometheus, and Grafana using Docker Compose
Command to run docker-compose.yml
```bash
$ docker compose up
```

You can access cAdvisor on http://localhost:28080, Prometheus on http://localhost:29090, and Grafana on http://localhost:23000.

CADVISOR: 28080
PROMETHEUS: 29090
GRAFANA: 23000


## Trouble Shooting

### Permission problem when attaching volumes on the hosts to the containers

```bash
bash init_dirs.sh
```

### Container Network 

Align static ips for the bridge and the containers.

```bash
docker inspect cadvisor-network
```
