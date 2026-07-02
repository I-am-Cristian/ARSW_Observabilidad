# Observabilidad - Lab

### Estructura del proyecto

![alt text](resources/image.png)

### Prueba inicial de la aplicación

Ejecute la aplicación:
- mvn spring-boot:run

Pruebe el estado del servicio:
- curl http://localhost:8081/actuator/health

![alt text](1.png)

{"status": "UP"}

