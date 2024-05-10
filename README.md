# ms-event-bus
Este microservicio proporciona RabbitMQ.

## Ejecución del Microservicio

### Requisitos Previos

- Docker instalado en tu máquina. Puedes descargar e instalar Docker desde [el sitio web oficial de Docker](https://www.docker.com/get-started).

### Pasos para Ejecutar el Microservicio

1. Abre una terminal o ventana de comandos.

2. Ejecuta el siguiente comando para iniciar el contenedor de RabbitMQ:
```bash
docker run -d --hostname rmq --name rabbit-server -p 8080:15672 -p 5672:5672 rabbitmq:3-management
```
3. Acceder a la interfaz de RabbitMQ en el puerto 5672.
