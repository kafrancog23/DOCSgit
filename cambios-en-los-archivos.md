# 馃捑 Cambios en los archivos



El comando **`git show`** nos muestra los cambios que han existido sobre un archivo y es muy 煤til para detectar cu谩ndo se produjeron ciertos cambios, qu茅 se rompi贸 y c贸mo lo podemos solucionar. Pero podemos ser m谩s detallados.

Si queremos ver la diferencia entre una versi贸n y otra, no necesariamente todos los cambios desde la creaci贸n del archivo, podemos usar el comando **`git diff commitA commitB`**.

Recuerda que puedes obtener el ID de tus commits con el comando **`git log`**.

### Comandos para analizar cambios en GIT

* **git init**: inicializar el repositorio
* **git add nombre\_de\_archivo.extensi贸n**: agregar el archivo al repositorio
* **git commit -m 鈥淢ensaje鈥?**: Agregamos los cambios para el repositorio
* **git add**: Agregar los cambios de la carpeta en la que nos encontramos agregar todo
* **git status**: visualizar cambios
* **git log nombre\_de\_archivos.extensi贸n**: hist贸rico de cambios con detalles
* **git push**: env铆a a otro repositorio remoto lo que estamos haciendo
* **git pull**: traer repositorio remoto
* **ls**: listado de carpetas en donde me encuentro. Es decir, como emplear dir en windows.
* **pwd**: ubicaci贸n actual
* **mkdir**: make directory nueva carpeta
* **touch archivo.extensi贸n**: crear archivo vac铆o
* **cat archivo.extensi贸n**: muestra el contenido del archivo
* **history**: historial de comandos utilizados durante esa sesi贸n
* **rm archivo.extensi贸n**: Eliminaci贸n de archivo
* **comando --help**: ayuda sobre el comando
* **git checkout**: traer cambios realizados
* **git rm --cached archivo.extensi贸n**: se utiliza para devolver el archivo que se tiene en ram. Cuando escribimos `git add`, lo devuelve a estado natural mientras est谩 en _staging_.
* **git config --list**: muestra la lista de configuraci贸n de git
* **git config --list --show-origin**: rutas de acceso a la configuraci贸n de git
* **git log archivo.extensi贸n**: muestra la historia del archivo
