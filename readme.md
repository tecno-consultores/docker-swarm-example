# docker-swarm-example

Para inicializar:
```bash
docker swarm init
```

Para desplegar servicio:
```bash
docker stack deploy -c example-swarm.yml example_service
```

Para eliminar servicio:
```bash
docker stack rm example_service
docker swarm leave --force
```

