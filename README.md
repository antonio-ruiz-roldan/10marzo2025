Proyecto Git Flow en PHP

Este proyecto es parte de un ejercicio practico para aprender a utilizar Git Flow en un entorno de desarrollo PHP.

# Uso de Git Flow en un Proyecto PHP

## Paso 1: Creación del repositorio y configuración inicial
1. He creado un repositorio en GitHub con el nombre `gitflow-php-RMM.
2. Lo he clonado en mi equipo con el comando `git clone`.
3. He inicializado Git Flow en el proyecto con `git flow init` y he creado la rama `develop`.

## Paso 2: Creación de un archivo PHP
1. Creé una nueva funcionalidad usando `git flow feature start crear-mi-archivo`.
2. Dentro de la carpeta `alumnos/`, creé el archivo `tu_nombre.php` con el siguiente contenido:
   ```php
   <?php
   echo "Hola, soy [Tu Nombre] y estoy aprendiendo Git Flow!";
   ?>

  ## Paso 3: Modificación de un archivo existente
1. Creé una nueva funcionalidad usando `git flow feature start modificar-index`.
2. Modifiqué `index.php` para incluir el archivo `tu_nombre.php` con la siguiente línea de código:
   ```php
   include "alumnos/tu_nombre.php";
   
  ## Paso 4: Resolución de conflictos
1. Modifiqué `index.php` en la misma línea que otro compañero.
2. Realicé un merge de ambas ramas y encontré un conflicto en `index.php`.
3. Resolví el conflicto manualmente, seleccionando el código correcto y eliminando los delimitadores.
4. Confirmé y subí los cambios a la rama `develop`.
  