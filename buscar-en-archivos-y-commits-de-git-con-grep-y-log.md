# 💾 Buscar en archivos y commits de Git con Grep y log



A medida que nuestro proyecto en Git se hace más grande, vamos a querer buscar ciertas cosas.

Por ejemplo: ¿cuántas veces en nuestro proyecto utilizamos la palabra _color_?

Para buscar, empleamos el comando `git grep color` y nos buscará en todo el proyecto los archivos en donde está la palabra _color_.

* Con `git grep -n color` nos saldrá un output el cual nos dirá en qué línea está lo que estamos buscando.
* Con `git grep -c color` nos saldrá un output el cual nos dirá cuántas veces se repite esa palabra y en qué archivo.
* Si queremos buscar cuántas veces utilizamos un atributo de HTML lo hacemos con `git grep -c "<p>"`.
