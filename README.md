
## Despliegue de apps Spring Boot y github.com

Crear archivo `system.properties` en el proyecto con el contenido:

```
java.runtime.version=17
```

1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el ordenador (ejecutar únicamente la primera vez que se instala git):
    1. `git config --global user.name "Alan Sastre"`
    2. `git config --global user.email alan@example.com`
3. Subir el proyecto a Github desde Intellij IDEA desde la opción: VCS > Share project on Github
4.  Desde Heroku, crear app y elegir método Github y buscar el respositorio subido
5. Habilitar deploy automático y ejecutar el Deploy

## Ejercicio 1

* Probar a empaquetar la aplicación con maven package desde Intellij IDEA

* Desde terminal en Intellij IDEA verificar que se ejecuta correctamente con el comando:


```
java -jar target/spring-deploy-1.0.jar
```

* Crear un perfil para dev y otro para test con una propiedad nueva que carguemos en el controlador.

## Ejercicio 2

Desplegar el API REST de Laptops en Heroku y verificar funcionamiento desde POSTMAN.


## Proveedores Cloud

* Heroku -- Java, Spring, PostgreSQL
* Netlify -- Frontend (React, Angular....)
* Vercel -- Frontend (React, Angular....)