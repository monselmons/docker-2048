# Docker Deployment AWS - 2048

Proyecto desplegado en AWS usando Docker y NGINX.

La aplicación consiste en un juego web 2048 ejecutado dentro de un contenedor Docker sobre una instancia EC2 de AWS.

---

# Tecnologías

- AWS EC2
- Docker
- Docker Compose
- NGINX
- Ubuntu Server 24.04
- HTML5
- CSS3
- JavaScript

---

# Requisitos

- Ubuntu Server 24.04
- Docker instalado
- Docker Compose instalado
- Puerto 80 habilitado en el Security Group

---

# Clonar Proyecto

```bash
git clone https://github.com/TU_USUARIO/docker-2048.git
cd docker-2048
```

---

# Construcción Manual

```bash
sudo docker build -t game2048 .
```

---

# Ejecución Manual

```bash
sudo docker run -d -p 80:80 game2048
```

---

# Despliegue Automático

```bash
sudo docker compose up -d
```

---

# Verificar Contenedores

```bash
sudo docker ps
```

---

# Acceso WEB

http://3.90.248.115

Varía si se cierra AWS

---

# Autor

Luis Monsalve
