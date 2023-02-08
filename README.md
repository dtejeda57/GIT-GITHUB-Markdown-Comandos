# GIT-GITHUB-Markdown-Comandos
Investigacion 1
David Francisco Tejeda Cabrera
09170350
Ciencia de datos en Python

**¿Qué es GIT?**
Es un sistema de control de versiones distribuido que rastrea los cambios en cualquier conjunto de archivos de computadora, utilizando generalmente por programadores para coordinar el trabajo que desarrollan en colaboración en un código fuente durante el desarrollo de software. 
Se trata de un sistema de control de versiones distribuido. Esto significa que cualquier desarrollador del equipo que tenga acceso puede gestionar el código fuente y su historial de cambios utilizando las herramientas de línea de comandos de Git.
A diferencia de los sistemas de control de versiones centralizados, Git ofrece ramas de características. Esto significa que cada ingeniero de software en el equipo puede dividir una rama de características que proporcionará un repositorio local aislado para hacer cambios en el código.
Git fue creado originalmente por Linus Torvalds en 2005 para el desarrollo del kernel de Linux, y otros desarrolladores del kernel contribuyeron a su desarrollo inicial. Desde 2005, Junio Hamano ha sido el mantenedor central. Al igual que con la mayoría de los otros sistemas de control de versiones distribuidos, y a diferencia de la mayoría de los sistemas cliente-servidor, cada directorio Git en cada computadora es un repositorio completo con un historial y capacidades completos de seguimiento de versiones, independientemente del acceso a la red o un servidor central. Git es un software gratuito y de código abierto distribuido bajo la licencia GPL-2.0

**¿Qué es GitHub?**
GitHub es un servicio basado en la nube que aloja un sistema de control de versiones (VCS) llamado Git. Éste permite a los desarrolladores colaborar y realizar cambios en proyectos compartidos, a la vez que mantienen un seguimiento detallado de su progreso.

**¿Qué es el control de versiones?**
El control de versiones es un sistema que ayuda a rastrear y gestionar los cambios realizados en un archivo o conjunto de archivos. Utilizado principalmente por ingenieros de software para hacer un seguimiento de las modificaciones realizadas en el código fuente, el sistema de control de versiones les permite analizar todos los cambios y revertirlos sin repercusiones si se comete un error.
En otras palabras, el control de versiones permite a los desarrolladores trabajar en proyectos simultáneamente. Les permite hacer tantos cambios como necesiten sin infringir o retrasar el trabajo de sus colegas.
Si esos cambios en el código fuente arruinan el proyecto cuando se implementan, GitHub hace que sea fácil revertirlos con unos pocos clics, y se recuperará la versión anterior del proyecto.
En síntesis, el control de versiones elimina los riesgos y el miedo a cometer demasiados errores. En cambio, proporciona la libertad de colaborar y desarrollar sin demasiadas preocupaciones.
¿Qué es Markdown?
Markdown es la forma de dar estilo al texto en la web. Controlas la forma en como se ve un documento; dando formato a las palabras como hacerlas negritas o itálicas, agregar imágenes, y creando listas, estás son solo algunas de las cosas que puedes hacer con Markdown. En general, Markdown es sólo un texto normal con un poco de caracteres no-alfabéticos en él, como # o *.
Puedes utilizar Markdown en la mayoría de los lugares de GitHub:
•	Gits
•	Comentarios en Issues y Pull Request
•	Archivos con extensión .mdo .markdown
Ejemplos
Texto
Es bastante sencillo convertir algunas palabras en **negritas** y otras en *italicas* con Markdown. Incluso puedes hacer un [link a Google](http://google.com\).

Es bastante sencillo convertir algunas palabras en negritas y otras en italicas con Markdown. Incluso puedes hacer un link a Google.

Sintaxis básica
Aquí un resumen de la sintaxis de Markdown que puedes utilizar en cualquier lugar de GitHub.com o en tus archivos de texto.
Encabezados
# Este es una etiqueta <h1>
## Este es una etiqueta <h2>
###### Este es una etiqueta <h6>

Énfasis
*Este texto estará en itálica*
_Este texto también estará en itálica_

**Este texto estará en negritas**
__Este texto también estará en negritas__
*Incluso **puedes** combinarlos*

Listas
Desordenadas
* Item 1
* Item 2
    * Item 2a
    * Item 2b
Ordenadas
1. Item 1
2. Item 2
3. Item 3
    * Item 3a
    * Item 3b

Imágenes
![GitHub Logo](/images/logo.png)

Formato:
![Atributo Alt](url "Atributo title Opcional")

Links
1. http://github.com - ¡link automático!

2. [GitHub](http://github.com)

3. [GitHub][id]

4. [GitHub][]
Link automático - Cualquier dirección explicita será convertida en un link.
Link en-línea - [Texto del Link](url).
Link por-referencia - [Texto del Link][id]. el id necesitará ser declarado en otra parte del documento así: [id]: url.
Link por-referencia automática - El id es el "Texto del Link", y también necesita ser declarado en otra parte del documento de igual manera que el "link por-referencia".

Citas
Esto es un párrafo normal:

> Y aquí está la cita que puede
> seguir en varios renglones, y tener anidado más
> > citas así, con un doble signo mayor-que.
Código en-línea
Creo que debería utilizar una etiqueta `<addr>` aquí.



**Entendiendo cómo funciona GIT**
GIT es el SCV (sistema de control de versiones) de código abierto más utilizado que te permite rastrear los cambios realizados en los archivos. Las empresas y los programadores suelen utilizar el GIT para colaborar en el desarrollo de software y aplicaciones.
Un proyecto GIT consta de tres secciones principales: el directorio de trabajo, el área de preparación y el directorio git.
El directorio de trabajo es donde se agregan, borran y editan los archivos. Luego, los cambios son preparados (indexados) en el área de preparación. Después de que confirmes tus cambios, la instantánea de los cambios se guardará en el directorio git.
Todo el mundo puede usar GIT ya que está disponible para Linux, Windows, Mac y Solaris. El software puede tener una fuerte curva de aprendizaje, pero hay muchos tutoriales disponibles para ayudar.
Comandos de GIT básicos
Aquí hay algunos comandos básicos de GIT que debes conocer:
* •	git init creará un nuevo repositorio local GIT. El siguiente comando de Git creará un repositorio en el directorio actual:
git init
* •	Como alternativa, puedes crear un repositorio dentro de un nuevo directorio especificando el nombre del proyecto:
git init [nombre del proyecto]
* •	git clone se usa para copiar un repositorio. Si el repositorio está en un servidor remoto, usa:
git clone nombredeusuario@host:/path/to/repository
* •	A la inversa, ejecuta el siguiente comando básico para copiar un repositorio local:
git clone /path/to/repository
* •	git add se usa para agregar archivos al área de preparación. Por ejemplo, el siguiente comando de Git básico indexará el archivo temp.txt:
git add <temp.txt>
* •	git commit creará una instantánea de los cambios y la guardará en el directorio git.
git commit –m “El mensaje que acompaña al commit va aquí”
* •	Ten en cuenta que los cambios confirmados no llegarán al repositorio remoto.
* •	git config puede ser usado para establecer una configuración específica de usuario, como el email, nombre de usuario y tipo de formato, etc. Por ejemplo, el siguiente comando se usa para establecer un email:
git config --global user.email tuemail@ejemplo.com
* •	La opción -global le dice a GIT que vas a usar ese correo electrónico para todos los repositorios locales. Si quieres utilizar diferentes correos electrónicos para diferentes repositorios, usa el siguiente comando:
git config --local user.email tuemail@ejemplo.com
* •	git status muestra la lista de los archivos que se han cambiado junto con los archivos que están por ser preparados o confirmados.
git status
* •	git push se usa para enviar confirmaciones locales a la rama maestra del repositorio remoto. Aquí está la estructura básica del código:
git push  origin <master>
* •	Reemplaza <master> con la rama en la que quieres enviar los cambios cuando no quieras enviarlos a la rama maestra.
* •	git checkout crea ramas y te ayuda a navegar entre ellas. Por ejemplo, el siguiente comando crea una nueva y automáticamente se cambia a ella:
command git checkout -b <branch-name>
* •	Para cambiar de una rama a otra, sólo usa:
git checkout <branch-name>
* •	git remote te permite ver todos los repositorios remotos. El siguiente comando listará todas las conexiones junto con sus URLs:
git remote -v
* •	Para conectar el repositorio local a un servidor remoto, usa este comando:
git remote add origin <host-or-remoteURL>
* •	Por otro lado, el siguiente comando borrará una conexión a un repositorio remoto especificado:
git remote <nombre-del-repositorio>
* •	git branch se usa para listar, crear o borrar ramas. Por ejemplo, si quieres listar todas las ramas presentes en el repositorio, el comando debería verse así:
git branch
* •	Si quieres borrar una rama, usa:
 git branch -d <branch-name>
* •	git pull fusiona todos los cambios que se han hecho en el repositorio remoto con el directorio de trabajo local.
git pull
* •	git merge se usa para fusionar una rama con otra rama activa:
git merge <branch-name>
* •	git diff se usa para hacer una lista de conflictos. Para poder ver conflictos con respecto al archivo base, usa:
git diff --base <file-name>
* •	El siguiente comando se usa para ver los conflictos que hay entre ramas antes de fusionarlas:
git diff <source-branch> <target-branch>
* •	Para ver una lista de todos los conflictos presentes usa:
git diff
* •	git tag marca commits específicos. Los desarrolladores lo usan para marcar puntos de lanzamiento como v1.0 y v2.0.
git tag 1.1.0 <instert-commitID-here>
* •	git log se usa para ver el historial del repositorio listando ciertos detalles de la confirmación. Al ejecutar el comando se obtiene una salida como ésta:
commit 15f4b6c44b3c8344caasdac9e4be13246e21sadw
Author: Alex Hunter <alexh@gmail.com>
Date:   Mon Oct 1 12:56:29 2016 -0600
* •	git reset sirve para resetear el index y el directorio de trabajo al último estado de confirmación.
git reset - -hard HEAD
* •	git rm se puede usar para remover archivos del index y del directorio de trabajo.
git rm filename.txt
* •	git stash guardará momentáneamente los cambios que no están listos para ser confirmados. De esta manera, pudes volver al proyecto más tarde.
git stash
* •	git show se usa para mostrar información sobre cualquier objeto git.
git show
* •	git fetch le permite al usuario buscar todos los objetos de un repositorio remoto que actualmente no se encuentran en el directorio de trabajo local.
git fetch origin
* •	git ls-tree te permite ver un objeto de árbol junto con el nombre y modo de cada ítem, y el valor blob de SHA-1. Si quieres ver el HEAD, usa:
git ls-tree HEAD
* •	git cat-file se usa para ver la información de tipo y tamaño de un objeto del repositorio. Usa la opción -p junto con el valor SHA-1 del objeto para ver la información de un objeto específico, por ejemplo:
git cat-file –p d670460b4b4aece5915caf5c68d12f560a9fe3e4
* •	git grep le permite al usuario buscar frases y palabras específicas en los árboles de confirmación, el directorio de trabajo y en el área de preparación. Para buscar por www.hostinger.com en todos los archivos, usa:
git grep “www.hostinger.com”
* •	gitk muestra la interfaz gráfica para un repositorio local. Simplemente ejecuta:
gitk
* •	git instaweb te permite explorar tu repositorio local en la interfaz GitWeb. Por ejemplo:
git instaweb –http=webrick
* •	git gc limpiará archivos innecesarios y optimizará el repositorio local.
git gc
* •	git archive le permite al usuario crear archivos zip o tar que contengan los constituyentes de un solo árbol de repositorio. Por ejemplo:
git archive - -format=tar master
* •	git prune elimina los objetos que no tengan ningún apuntador entrante.
git prune
* •	git fsck realiza una comprobación de integridad del sistema de archivos git e identifica cualquier objeto corrupto
git fsck
* •	git rebase se usa para aplicar ciertos cambios de una rama en otra. Por ejemplo:
git rebase master

