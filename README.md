

### Pasos para no redirigir

1. Entramos a PhpMyAdmin
2. Vamos hacia SQL e introducimos:

```
UPDATE ps_configuration SET value = '1' WHERE name = 'PS_SSL_ENABLED';
UPDATE ps_configuration SET value = '1' WHERE name = 'PS_SSL_ENABLED_EVERYWHERE';
```
