﻿# Pidecola Data Analyser

Este proyecto en C está diseñado para leer información de un disco y permitir la búsqueda de registros por **carnet de estudiante** o **código de materia**. Esto calcula la probabilidad que tiene un estudiante o una seccion de una materia de subir a clases presenciales en la universidad.

**Estructura del proyecto:**

* **main.c:** Punto de entrada del programa.
* **calc_prob.c:** Funciones para calcular las probabilidades.
* **files_finder.c:** Funciones para realizar las búsquedas dentro de los archivos.
* **queue.c:** Definición de las estructura de cola utilizada.
* **Makefile:** Archivo que facilita la compilación del proyecto.

**Cómo utilizar:**

1. Compilar el código: `make` desde el directorio raiz del proyecto.
2. Ejecutar el programa: `./pidecola.out`
3. Seguir las instrucciones en pantalla para realizar las búsquedas.
