# Curso de Programación Web con Spring Boot Framework.

## Registro de Usuarios - Aplicación

Este repositorio contiene una aplicación de registro de usuarios desarrollada en Java utilizando el framework Spring Boot. La aplicación permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en una base de datos de usuarios utilizando PostgreSQL.

## Funcionalidades

- Crear un nuevo usuario con su información básica.
- Leer la lista completa de usuarios registrados.
- Actualizar la información de un usuario existente.
- Eliminar un usuario de la base de datos.

## Tecnologías Utilizadas

- Java
- Spring Boot
- Spring Data JPA
- RESTful API
- PostgreSQL

## Instrucciones de Uso

1. Clona este repositorio en tu máquina local.
2. Configura la conexión a la base de datos PostgreSQL en `src/main/resources/application.properties`. Asegúrate de proporcionar la URL, el nombre de usuario y la contraseña correspondientes.
3. Ejecuta la aplicación utilizando tu IDE preferido o mediante la línea de comandos.
4. Accede a la API a través de las rutas definidas en el controlador (`UserController`) para realizar las operaciones CRUD.

## Ejemplos de Uso

### Obtener todos los usuarios

Envía una solicitud GET a `http://localhost:8080/api/v1/users` para obtener la lista de usuarios registrados.

### Crear un nuevo usuario

Envía una solicitud POST a `http://localhost:8080/api/v1/users` con los datos del usuario en el cuerpo de la solicitud.

### Actualizar un usuario

Envía una solicitud PUT a `http://localhost:8080/api/v1/users` con los datos actualizados del usuario en el cuerpo de la solicitud.

### Eliminar un usuario

Envía una solicitud DELETE a `http://localhost:8080/api/v1/users/{userId}` para eliminar un usuario por su ID.

## Contribuciones

Las contribuciones son bienvenidas. Si encuentras un error o tienes alguna mejora que proponer, por favor crea un Pull Request o abre un Issue en este repositorio.

## Licencia

Este proyecto está bajo la Licencia [MIT](LICENSE).