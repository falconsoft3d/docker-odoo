# Comandos de docker
```
docker ps
```


# Start a PostgreSQL server
```
docker run -d -e POSTGRES_USER=odoo -e POSTGRES_PASSWORD=odoo -e POSTGRES_DB=postgres --name db postgres:10
```

# Start Odoo
```
docker pull odoo
```
