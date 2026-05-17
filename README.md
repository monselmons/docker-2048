# Docker Deployment AWS

Proyecto desplegado en AWS usando Docker y NGINX.

## Tecnologías

- AWS EC2
- Docker
- NGINX
- Ubuntu Server 24.04

## Construcción

```bash
sudo docker build -t game2048 .
```

## Ejecución

```bash
sudo docker run -d -p 80:80 game2048
```

## Acceso WEB

http://3.90.248.115

## Autor

Luis Monsalve
