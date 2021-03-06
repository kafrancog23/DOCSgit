# 馃捑 Conceptos



Un editor de c贸digo o **IDE** es una herramienta que nos brinda muchas ayudas para escribir c贸digo, algo as铆 como un bloc de notas muy avanzado. Los editores m谩s populares son VSCode, Sublime Text y Atom, pero no es obligatorio usar alguno de estos para programar. Conoce m谩s a fondo sobre [qu茅 es un IDE](https://platzi.com/blog/que-es-ide-editor-de-texto/).

### Tipos de archivos y sus diferencias:

* **Archivos de Texto (.txt)**: Texto plano normal y sin nada especial. Lo vemos igual sin importar d贸nde lo abramos, ya sea con el bloc de notas o con editores de texto avanzados.
* **Archivos RTF (.rtf)**: Podemos guardar texto con diferentes tama帽os, estilos y colores. Pero si lo abrimos desde un editor de c贸digo, vamos a ver que es mucho m谩s complejo que solo el texto plano. Esto es porque debe guardar todos los estilos del texto y, para esto, usa un c贸digo especial un poco dif铆cil de entender y muy diferente a los textos con estilos especiales al que estamos acostumbrados.
* **Archivos de Word (.docx)**: Podemos guardar im谩genes y texto con diferentes tama帽os, estilos o colores. Al abrirlo desde un editor de c贸digo podemos ver que es c贸digo binario, muy dif铆cil de entender y muy diferente al texto al que estamos acostumbrados. Esto es porque Word est谩 optimizado para entender este c贸digo especial y representarlo gr谩ficamente.

Recuerda que debes habilitar la opci贸n de ver la extensi贸n de los archivos, de lo contrario, solo podr谩s ver su nombre. La forma de hacerlo en Windows es `Vista > Mostrar u ocultar > Extensiones de nombre de archivo`.

### Conceptos importantes de Git

* Bug: Error en el c贸digo
* Repository: Donde se almacena todo el proyecto, el cual puede vivir tanto en local como en remoto. El repositorio guarda un historial de versiones y, m谩s importante, de la relaci贸n de cada versi贸n con la anterior para que pueda hacerse el 谩rbol de versiones con las diferentes ramas.
* Fork: Si en alg煤n momento queremos contribuir al proyecto de otra persona, o si queremos utilizar el proyecto de otro como el punto de partida del nuestro. Esto se conoce como 鈥渇ork鈥?.
* Clone: Una vez se decide hacer un fork , hasta ese momento s贸lo existe en GitHub. Para poder trabajar en el proyecto, toca clonar el repositorio elegido al computador personal.
* Branch: Es una bifurcaci贸n del proyecto que se est谩 realizando para anexar una nueva funcionalidad o corregir un bug.
* Master: Rama donde se almacena la 煤ltima versi贸n estable del proyecto que se est谩 realizando. La rama master es la que est谩 en producci贸n en cada momento (o casi) y deber铆a estar libre de bugs. As铆, si esta rama est谩 en producci贸n, sirve como referente para hacer nuevas funcionalidades y/o arreglar bugs de 煤ltima hora.
* Commit: consiste en subir cosas a la versi贸n local del repositorio. De esta manera se puede trabajar en la rama de forma local sin tener que modificar ninguna versi贸n en remoto ni tener que tener la 煤ltima versi贸n remota, cosa muy 煤til en grandes desarrollos trabajados por varias personas.
* Push: Consiste en enviar todo lo que se ha confirmado con un commit al repositorio remoto. Aqu铆 es donde se une nuestro trabajo con el de los dem谩s.
* Checkout: Acci贸n de descargarse una rama del repositorio GIT local (s铆, GIT tiene su propio repositorio en local para poder ir haciendo commits) o remoto.
* Fetch: Actualiza el repositorio local bajando datos del repositorio remoto al repositorio local sin actualizarlo, es decir, se guarda una copia del repositorio remoto en el local.
* Merge: La acci贸n de merge es la continuaci贸n natural del fetch. El merge permite unir la copia del repositorio remoto con tu repositorio local, mezclando los diferentes c贸digos.
* Pull: Consiste en la uni贸n del fetch y del merge, esto es, recoge la informaci贸n del repositorio remoto y luego mezcla el trabajo en local con esta.
* Diff: Se utiliza para mostrar los cambios entre dos versiones del mismo archivo.
