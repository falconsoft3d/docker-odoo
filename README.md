# Instalar Odoo
```
sudo su
sudo apt-get update
sudo apt-get remove docker docker-engine docker.io
sudo apt install docker.io
sudo systemctl start docker
sudo systemctl enable docker
docker --version

docker run -d -e POSTGRES_USER=odoo -e POSTGRES_PASSWORD=odoo -e POSTGRES_DB=postgres --name db postgres:10
docker pull odoo

docker run -p 8069:8069 --name odoo --link db:db -t odoo
```

# Comandos de docker


# Instalar Dockers
```
sudo apt install docker.io
```

# Listar Dockers
```
docker ps
```

# Parar Dockers
```
docker stop
```

# Borrar Dockers
```
docker rm
```


# Start a PostgreSQL server
```
docker run -d -e POSTGRES_USER=odoo -e POSTGRES_PASSWORD=odoo -e POSTGRES_DB=postgres --name db postgres:10
```

# Start Odoo
```
docker pull odoo
```

# Links:
```
https://hub.docker.com
```
