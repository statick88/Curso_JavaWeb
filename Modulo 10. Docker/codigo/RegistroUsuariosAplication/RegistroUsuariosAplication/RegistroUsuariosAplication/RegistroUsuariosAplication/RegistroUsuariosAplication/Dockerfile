# Establece la imagen base para la aplicación Spring Boot
FROM openjdk:11-jdk-slim AS build
LABEL authors="dsaav"
# Establece el directorio de trabajo dentro del contenedor
WORKDIR /app

# Copia el archivo JAR de la aplicación Spring Boot a la imagen
COPY target/registro-usuarios-app.jar ./app.jar

# Expone el puerto 8080 en el contenedor
EXPOSE 8081

# Comando para ejecutar la aplicación Spring Boot
CMD ["java", "-jar", "app.jar"]


# Agrega una segunda etapa para la base de datos PostgreSQL
FROM postgres:latest AS database

# Configura las variables de entorno para la base de datos PostgreSQL
ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=1234
ENV POSTGRES_DB=db

# Expone el puerto 5432 en el contenedor
EXPOSE 5432
