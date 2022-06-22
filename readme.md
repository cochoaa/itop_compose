## Configuracion para itop base (sin mysql)
Se debe crear una base datos primero

## Crear base de datos en mysql

```sql
create database qp_itop;
create  user 'u_itop'@'%' IDENTIFIED BY 'yourpass';
GRANT ALL PRIVILEGES ON qp_itop.*  TO 'u_itop'@'%';
```

```bash
docker-compose up -d
docker exec itop chown www-data:www-data /var/www/html/conf
```