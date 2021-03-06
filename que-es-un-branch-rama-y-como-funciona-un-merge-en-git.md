# 馃捑 驴Qu茅 es un Branch (rama) y c贸mo funciona un Merge en Git?

En GIT, una **rama o branch** es una versi贸n del c贸digo del proyecto sobre el que est谩s trabajando. Estas ramas ayudan a mantener el orden en el control de versiones y manipular el c贸digo de forma segura.\
Por defecto, el proyecto se crea en una rama llamada Main (anteriormente conocida como Master). Cada vez que a帽ades c贸digo y guardas los cambios, est谩s haciendo un commit, que es a帽adir el nuevo c贸digo a una rama. Esto genera nuevas versiones de esta rama o branch, hasta llegar a la versi贸n actual de la rama Main.

Cuando decides hacer experimentos, puedes generar ramas experimentales (usualmente llamadas development), que est谩n basadas en alguna rama main, pero sobre las cuales puedes hacer cambios a tu gusto sin necesidad de afectar directamente al c贸digo principal.

En otros casos, si encuentras un bug o error de c贸digo en la rama Main (que afecta al proyecto en producci贸n), tendr谩s que crear una nueva rama (que usualmente se llaman bug fixing o hot fix) para hacer los arreglos necesarios. Cuando los cambios est茅n listos, los tendr谩s que fusionar con la rama Main para que los cambios sean aplicados. Para esto, se usa un comando llamado _Merge_, que mezcla los cambios de la rama que originaste a la rama Main.

**Todos los commits se aplican sobre una rama**. Por defecto, siempre empezamos en la rama Main (pero puedes cambiarle el nombre si no te gusta) y generamos nuevas ramas, a partir de esta, para crear flujos de trabajo independientes.

### Checkout y merge

Producir una nueva rama se conoce como **Checkout**. Unir dos ramas lo conocemos como **Merge**.

Cuando haces merge de estas ramas con el c贸digo principal, su c贸digo se fusiona, originando una nueva versi贸n de la rama Master (o main) que ya tiene todos los cambios que aplicaste en tus experimentos o arreglos de errores.

Podemos generar todas las ramas y commits que queramos. De hecho, podemos aprovechar el registro de cambios de Git para producir ramas, traer versiones viejas del c贸digo, arreglarlas y combinarlas de nuevo para mejorar el proyecto.

Solo ten en cuenta que combinar estas ramas (hacer 鈥渕erge鈥?) puede generar conflictos. Algunos archivos pueden ser diferentes en ambas ramas. Git es muy inteligente y puede intentar unir estos cambios autom谩ticamente, pero no siempre funciona. En algunos casos, somos nosotros los que debemos resolver estos conflictos _a mano_.
