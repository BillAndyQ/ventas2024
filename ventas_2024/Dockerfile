FROM openjdk:17-jdk-slim

# Definir el archivo JAR a copiar
ARG JAR_FILE=target/punto_venta-0.0.1.jar

# Copiar el archivo JAR al contenedor
COPY ${JAR_FILE} app_ventas.jar

# Exponer el puerto de la aplicación
EXPOSE 8080

# Ejecutar la aplicación Java
ENTRYPOINT ["java", "-jar", "app_ventas.jar"]
