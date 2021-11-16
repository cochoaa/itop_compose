## Crear base de datos en mysql

```
create  user 'u_itop'@'0.0.0.0' IDENTIFIED BY 'yourpass';
GRANT ALL PRIVILEGES ON qp_itop.*  TO 'u_itop'@'0.0.0.0';
```