# docker_odoo10
Necesitamos primero instalar docker,  despues instalar docker-compose

Para Ejecutar Odoo 10 necesitamos 2 Contenedores:
1) La aplicación Odoo 10
2) Postgresql 9.5

Para levantar estos servicios utilizaremos docker-compose, generamos el documento donde estara la configuracion detallada de cada unos de los servicios con su respectiva imagen.

docker_odoo10
  ---docker_compose.yml

Ejecutamos el comando
  docker-compose up -d

Verificamos que los servicios esta activos entrando al http://localhost:8069

Detener los contenedores
  docker-compose stop


