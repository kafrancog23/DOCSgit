# 💾 Comandos y recursos colaborativos en Git y GitHub



* `git shortlog -sn`: muestra cuantos commit han hecho cada miembro del equipo.
* `git shortlog -sn --all`: muestra cuantos commit han hecho cada miembro del equipo, hasta los que han sido eliminados.
* `git shortlog -sn --all --no-merge`: muestra cuantos commit ha hecho cada miembro, quitando los eliminados sin los merges.
* `git blame ARCHIVO`: muestra quien hizo cada cosa línea por línea.
* `git COMANDO --help`:muestra como funciona el comando.
* `git blame ARCHIVO -Llinea_inicial,linea_final`: muestra quien hizo cada cosa línea por línea, indicándole desde qué línea ver. Ejemplo -L35,50.
* `git branch -r`: se muestran todas las ramas remotas.
* `git branch -a`: se muestran todas las ramas, tanto locales como remotas.
