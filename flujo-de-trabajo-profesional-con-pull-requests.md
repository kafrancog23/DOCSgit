# 🦊 Flujo de trabajo profesional con Pull requests



En un entorno profesional normalmente se bloquea la rama **master**, y para enviar código a dicha rama pasa por un _code review_ y luego de su aprobación se unen códigos con los llamados _merge request_.

Para realizar pruebas enviamos el código a servidores que normalmente los llamamos _staging develop_ (servidores de pruebas) luego de que se realizan las pruebas pertinentes tanto de código como de la aplicación estos pasan al servidor de producción con el ya antes mencionado _merge request_.

Los PR (pull requests) son la base de la colaboración a proyectos Open Source, si tienen pensando colaborar en alguno es muy importante entender esto y ver cómo se hace en las próximas clases. Por lo general es forkear el proyecto, implementar el cambio en una nueva rama, hacer el PR y esperar que los administradores del proyecto hagan el merge o pidan algún cambio en el código o commits que hiciste.

### Proceso de un pull request para trabajo en producción:

* Un pull request es un estado intermedio antes de enviar el merge.
* El pull request permite que otros miembros del equipo revisen el código y así aprobar el merge a la rama.
* Permite a las personas que no forman el equipo, trabajar y colaborar con una rama.
* La persona que tiene la responsabilidad de aceptar los pull request y hacer los merge tienen un perfil especial y son llamados DevOps\

*   **Pull request** es una funcionalidad de Github (en Gitlab llamada _merge request_ y en Bitbucket _push request_), en la que un colaborador pide que revisen sus cambios antes de hacer _merge_ a una rama, normalmente _master_ (ahora conocida como _main_).

    Al hacer un pull request, se genera una conversación que pueden seguir los demás usuarios del repositorio, así como autorizar y rechazar los cambios.

    ### Cómo se realiza un pull request

    * Se trabaja en una rama paralela los cambios que se desean `git checkout -b <rama>`.
    * Se hace un commit a la rama `git commit -am '<Comentario>'`.
    * Se suben al remoto los cambios `git push origin <rama>`.
    * En GitHub se hace el pull request comparando la rama master con la rama del fix.
    * Uno, o varios colaboradores revisan que el código sea correcto y dan feedback (en el chat del pull request).
    * El colaborador hace los cambios que desea en la rama y lo vuelve a subir al remoto (automáticamente jala la historia de los cambios que se hagan en la rama, en remoto).
    * Se aceptan los cambios en GitHub.
    * Se hace merge a master desde GitHub.

    **Importante**: Cuando se modifica una rama, también se modifica el pull request.
