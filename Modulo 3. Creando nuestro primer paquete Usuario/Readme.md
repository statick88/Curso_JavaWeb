# Módulo 3: Creando nuestro primer paquete Usuario.

## Creando el paquete Usuario

Nos dirigimos a nuestro directorio que contiene a nuestra aplicación principal RegistroUsuariosApplication.java y creamos un nuevo package llamado **Users**.

![Alt text](img/image.png)

Ahora creamos una clase llamada Users y le agregamos los siguientes atributos:

```java

package com.example.RegistroUsuariosApplication.Users;

public class User {

    private String name;

    private String email;

    private String password;

    private String phone;

    private String address;

    private String city;
}

```

Tambien creamos un constructor vacio.

![Alt text](img/image-1.png)

![Alt text](img/image-2.png)

Tambien agregamos un constructor cargado de información

![Alt text](img/image-3.png)

Ahora agregamos los Getter and Setter.

![Alt text](img/image-4.png)

Finalmente probamos en el navegador o mediante Thunder Client.

![Alt text](img/image-5.png)

![Alt text](img/image-6.png)