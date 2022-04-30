# 💾 Volver en el tiempo en nuestro repositorio



El comando **`git checkout`** + `ID del commit` nos permite viajar en el tiempo. Podemos volver a cualquier versión anterior de un archivo específico o incluso del proyecto entero. Esta también es la forma de crear ramas y movernos entre ellas.

También hay una forma de hacerlo un poco más “ruda”: usando el comando `git reset`. En este caso, no solo “volvemos en el tiempo”, sino que borramos los cambios que hicimos después de este commit.

Hay dos formas de usar `git reset`: con el argumento `--hard`, borrando toda la información que tengamos en el área de staging (y perdiendo todo para siempre). O, un poco más seguro, con el argumento `--soft`, que mantiene allí los archivos del área de staging para que podamos aplicar nuestros últimos cambios pero desde un commit anterior.

### Cómo usar Git Reset

Para volver a commits previos, borrando los cambios realizados desde ese commit, podemos utilizar:

* git reset --soft \[SHA 1]: elimina los cambios hasta el staging area
* git reset --mixed \[SHA 1]: elimina los cambios hasta el working area
* git reset --hard \[SHA 1]: regresa hasta el commit del \[SHA-1]\
  Donde el SHA-1 es el identificador del commit
