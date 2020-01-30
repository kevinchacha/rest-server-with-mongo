# servidor restful con nodejs

En este servidor se podrá hacer peticiones para modificar los registros de una base moongosee de datos local
o en línea a traves de llamados get,post,put y delete.
recuerda instalar los paquetes

```
npm install
```
ejecucion

```
node server/server
```

Listar usaurios
llamado get
```
localhost:[puerto_asignado]/usuario
```
Registrar usaurios
llamado post
```
localhost:[puerto_asignado]/usuario
ingresos:
    nombre-
    email-
    password-
    role-'admin_role' o 'user_role'
    img-
```
Editar usaurios
llamado put
```
localhost:[puerto_asignado]/usuario/:id
ingresos:
    nombre-
    email-
    password-
    role-'admin_role' o 'user_role'
    img-
```

Eliminar usaurios
llamado delete
nota: esta peticion no es buena para bases de datos, no es bueno eliminar datos de la base
dado que siempre es bueno tener un buen registro de todos los sucesos.
```
localhost:[puerto_asignado]/usuario/:id

```
