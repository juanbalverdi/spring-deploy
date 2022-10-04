
## Despliegue de apps Spring Boot y github.com

Crear archivo `system.properties` en el proyecto con el contenido:

```
java.runtime.version=17
```

1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el ordenador
    1. `git config --global user.name "Alan Sastre"`
    2. `git config --global user.email alan@example.com`
3. Subir el proyecto a Github desde Intellij IDEA desde la opción: VCS > Share project on Github
4.  Desde Heroku, crear app y elegir método Github y buscar el respositorio subido
5. Habilitar deploy automático y ejecutar el Deploy

    