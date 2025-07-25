
## Glosario de Terminos
<!-- Definiciones de Anner -->
**1. Archivo git**

Archivo `.git` sin formato, que siempre está en la raíz de un árbol de trabajo y que apunta al directorio Git, que tiene todo el repositorio de Git y sus metadatos. Puede ver este archivo para el repositorio en la línea de comandos con `git rev-parse --git-dir`. Es el repositorio real.

**2. Bifurcación**

Una bifurcación es una copia personal del repositorio de otro usuario que se aloja en tu cuenta. Las bifurcaciones permiten realizar cambios libremente en un proyecto sin que el repositorio ascendente original se vea afectado. También puede abrir una solicitud de incorporación de cambios en el repositorio ascendente y mantener la bifurcación sincronizada con los últimos cambios, ya que los dos repositorios siguen conectados.

**3. Checkout**

Puede usar `git checkout` en la línea de comandos para crear una rama, cambiar la rama de trabajo actual a otra o incluso cambiar a otra versión de un archivo desde otra rama con `git checkout [branchname] [path to file]`. La acción de "extracción del repositorio" actualiza todo o parte del árbol de trabajo con un objeto de árbol o un blob de la base de datos de objetos, y actualiza el índice y HEAD si todo el árbol de trabajo apunta a una nueva rama.



## Definiciones de comandos de git

**Git:**  
Git es un sistema de control de versiones distribuido que permite gestionar y registrar los cambios en archivos de código fuente durante el desarrollo de proyectos.

### Comandos basicos de Git

- `git init`: Inicializa un nuevo repositorio Git en el directorio actual.
- `git clone <url>`: Clona un repositorio remoto en tu máquina local.
- `git status`: Muestra el estado de los archivos en el directorio de trabajo y el área de preparación.
- `git add <archivo>`: Agrega archivos al área de preparación (staging area).
- `git commit -m "mensaje"`: Guarda los cambios agregados con un mensaje descriptivo.
- `git pull`: Descarga y fusiona los cambios del repositorio remoto al local.
- `git push`: Sube los cambios confirmados al repositorio remoto.
- `git log`: Muestra el historial de confirmaciones (commits) del repositorio.
- `git branch`: Lista, crea o elimina ramas en el repositorio.
- `git checkout <rama>`: Cambia a otra rama o restaura archivos.
- `git merge <rama>`: Fusiona la rama especificada con la rama actual.

Cada comando ayuda a gestionar el flujo de trabajo y la colaboración en proyectos de software.
Definiciones de comandos de git


Hola MUNDO EN MD.

