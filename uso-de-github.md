---
description: >-
  GitHub es una plataforma que nos permite guardar repositorios de Git que
  podemos usar como servidores remotos y ejecutar algunos comandos de forma
  visual e interactiva.
---

# 🦊 Uso de GitHub



Luego de crear nuestra cuenta, podemos crear o importar repositorios, crear organizaciones y proyectos de trabajo, descubrir repositorios de otras personas, contribuir a esos proyectos, dar estrellas y muchas otras cosas.

El `README.md` es el archivo que veremos por defecto al entrar a un repositorio. Es una muy buena práctica configurarlo para describir el proyecto, los requerimientos y las instrucciones que debemos seguir para contribuir correctamente.

Para clonar un repositorio desde GitHub (o cualquier otro servidor remoto) debemos copiar la URL (por ahora, usando `HTTPS`) y ejecutar el comando `git clone` + la URL que acabamos de copiar. Esto descargará la versión de nuestro proyecto que se encuentra en GitHub.

Sin embargo, esto solo funciona para las personas que quieren empezar a contribuir en el proyecto.

### Cómo conectar un repositorio de Github a nuestro documento local

Si queremos conectar el repositorio de GitHub con nuestro repositorio local, que creamos usando el comando `git init`, debemos ejecutar las siguientes instrucciones:

*
  1. PGuardar la URL del repositorio de GitHub con el nombre de origin

```
git remote add origin URL
```

*
  1. Verificar que la URL se haya guardado correctamente:

```
git remote
git remote -v
```

*
  1. Traer la versión del repositorio remoto y hacer _merge_ para crear un _commit_ con los archivos de ambas partes. Podemos usar `git fetch` y `git merge` o solo `git pull` con el _flag_ `--allow-unrelated-histories`:

```
git pull origin master --allow-unrelated-histories
```

*
  1. Por último, ahora sí podemos hacer `git push` para guardar los cambios de nuestro repositorio local en GitHub:

```
git push origin master
```
