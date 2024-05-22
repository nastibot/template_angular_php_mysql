FROM mysql:5.7
#Agregar scripts SQL que se ejecutarán al crear la base de datos

COPY ./CreateDatabase.sql /docker-entrypoint-initdb.d/CreateDatabase.sql
# La imagen mysql:5.7 tiene el valor predeterminado de ejecutar todos los scripts SQL desde la carpeta docker-entrypoint-initdb.d al iniciar el contenedor, por lo que si es necesario construir y configurar la base de datos, utilice este paso para hacerlo.
