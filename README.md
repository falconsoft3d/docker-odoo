# Instalar Odoo
```
sudo su
sudo apt install docker.io   "o"  snap  install docker
docker run -d -e POSTGRES_USER=odoo -e POSTGRES_PASSWORD=odoo -e POSTGRES_DB=postgres --name db postgres:10
docker pull odoo
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
