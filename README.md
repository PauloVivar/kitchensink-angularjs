## Simple Java Application

Aplicacion simple de Java dockerizada

Explicación de los cambios realizados:
1.	Se ha añadido un servicio nginx al archivo docker-compose.
2.	El servicio srvwildfly ya no expone los puertos 8080 y 9990 directamente.
3.	El servicio con Nginx está configurado para escuchar en el puerto 8880 y redirigir el tráfico al servicio srvwildfly.
4.	La configuración de Nginx (nginx.conf) maneja las solicitudes entrantes.


