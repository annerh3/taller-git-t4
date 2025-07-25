## Glosario de Terminos
<!-- Definiciones de Anner -->
**1. Archivo git**

Archivo `.git` sin formato, que siempre está en la raíz de un árbol de trabajo y que apunta al directorio Git, que tiene todo el repositorio de Git y sus metadatos. Puede ver este archivo para el repositorio en la línea de comandos con `git rev-parse --git-dir`. Es el repositorio real.

**2. Bifurcación**

Una bifurcación es una copia personal del repositorio de otro usuario que se aloja en tu cuenta. Las bifurcaciones permiten realizar cambios libremente en un proyecto sin que el repositorio ascendente original se vea afectado. También puede abrir una solicitud de incorporación de cambios en el repositorio ascendente y mantener la bifurcación sincronizada con los últimos cambios, ya que los dos repositorios siguen conectados.

**3. Checkout**

Puede usar `git checkout` en la línea de comandos para crear una rama, cambiar la rama de trabajo actual a otra o incluso cambiar a otra versión de un archivo desde otra rama con `git checkout [branchname] [path to file]`. La acción de "extracción del repositorio" actualiza todo o parte del árbol de trabajo con un objeto de árbol o un blob de la base de datos de objetos, y actualiza el índice y HEAD si todo el árbol de trabajo apunta a una nueva rama.

<!-- Definiciones de Héctor -->