## uso

```bash
  docker-compose up -d
```

**esperar un rato**
```bash
  docker exec -it db mysql -u root -p
```

cuando pida la password colocar **root**

dentro de la bash del contenedor fijarse si funciono todo bien

```bash
  USE db;
  SELECT * FROM usuarios;
```

