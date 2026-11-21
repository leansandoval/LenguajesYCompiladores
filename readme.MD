# Lenguajes y Compiladores
Repositorio del Trabajo Practico Compilador de la materia Lenguajes y Compiladores (3663) - 1C 2025 - UNLaM.

[Repositorio de la Materia](https://github.com/Lenguajes-y-Compiladores-UnLaM)

## Información de la Asignatura
* **Carrera**: Ingeniería en Informática
* **Asignatura**: Lenguajes y Compiladores (3663)
* **Cuatrimestre**: Primer Cuatrimestre
* **Año**: 2025
* **Grupo**: 9

## Trayecto - Infraestructura

* **Año académico**: Cuarto Año - Segundo Cuatrimestre
* **Responsable / Jefe de catedra**: Villareal, Hernan Pablo
* **Carga horaria semanal**: 4 hs
* **Carga horaria total**: 64 hs
* **Modalidad**: Virtual
* **Correlativa anterior**: Autómatas y Gramática (3657)

## Docentes
* Carrizo, Daniel Nestor
* Pin Etchave, Eleazar Patricio
* Villareal, Hernan Pablo

## Integrantes
| Apellido/s | Nombre/s |
|--|--|
| Castellana Pérez | Julian Alejandro |
| Galzerano | Matias Nahuel |
| Ocampo | Nicole Fabiana |
| Sandoval Vasquez | Juan Leandro |

## Unidad 1 - Perspectiva histórica.
* Primeros lenguajes de alto nivel.
* Relaciones entre los diferentes lenguajes de programación.
* Diagrama de interrelación entre los diferentes lenguajes, basado en la influencia de unos en otros.

## Unidad 2 - Estructura de los lenguajes de programación.


* Sintaxis, semántica y pragmática.
* Procesamiento de los lenguajes.
* Interpretación.
* Compilación.
* Lenguajes estáticos.
* Lenguajes basados en la pila.
* Lenguajes dinámicos.

## Unidad 3 - Sintaxis.
* Reglas léxicas.
* Reglas gramaticales.
* Metalenguajes.
* BNF.
* Árbol de Parsing.
* Impacto de la recursividad sobre la evaluación de expresiones.
* Influencia de la sintaxis sobre la claridad: formato de las instrucciones, comentarios, puntuación.

## Unidad 4 - Introducción a los compiladores.
* Compilación e interpretación.
* Ensambladores y compiladores.
* Cantidad de pasadas.
* Conversores fuente-fuente.
* Compiladores incrementales.
* Autocompiladores.
* Metacompiladores.
* Compilaciones Separadas.
* Vinculación.
* Descompiladores.
* Salidas del compilador.
* Notaciones para representar implementaciones.
* Diagramas T.

## Unidad 5 - Estructura general de un compilador.
* Relación entre los tipos de gramáticas y la estructura de los compiladores.
* Tabla de símbolos.
* Tabla de palabras reservadas.
* Mecanismo de acceso.

## Unidad 6 - Analizador léxico.
* Construcción de autómatas finitos a partir de gramáticas regulares.
* Implementación de analizadores léxicos mediante estructuras de control clásicas y mediante arreglos de punteros. 
* Utilización de Flex.

## Unidad 7 - Tabla de símbolos.
* Problemas de alcance.
* Relación entre la estructura en tiempo de ejecución y la tabla de símbolos.
* Etapas en la construcción de la tabla de símbolos.

## Unidad 8 - Análisis sintáctico.
* Análisis sintáctico descendente.
* Análisis sintáctico ascendente.
* Retrocesos.
* Detección y reporte de errores.
* Análisis sintáctico descendente predictivo.
* Conflictos desplazamiento-reducción.
* Conflictos reducción-reducción.
* Utilización de un analizador sintáctico.
* Bison/Yacc.

## Unidad 9 - Árboles sintácticos.
* Traducción guiada por la sintaxis.
* Semántica estática.
* Comprobación de tipos.
* Grafo de las alternativas en la generación de código: árbol sintáctico, tercetos, tercetos indirectos, cuartetos, notación polaca inversa.
* Caminos posibles. 

## Unidad 10 - Generación de código.
* Generación de código intermedio.
* Generación de código ejecutable.
* Relleno con retroceso.
* Nociones de manejo de errores.
* Nociones de optimización de código.

## Unidad 11 - Tipos de Datos.
* Su tratamiento en compiladores.
* El concepto de binding.
* Entidades y atributos.
* Binding dinámico y binding estático.
* Variables.
* Binding de alcance, de almacenamiento, de valor y de tipo.
* Binding de tipo e interpretación.
* Unidades de programa.
* Estructura en tiempo de ejecución.

## Plantilla para TP Integrador usando Flex y Bison (C)

### Prerequisitos. 

Para poder usar esta plantilla deberá:

1. Instalar [flex](https://github.com/westes/flex)

2. Instalar [bison](https://www.gnu.org/software/bison/)

3. Instalar [gcc](https://gcc.gnu.org/)

#### Windows

Descargue los instaladores para Windows de las siguientes páginas:

1. [Flex](http://gnuwin32.sourceforge.net/packages/flex.htm)
2. [Bison](http://gnuwin32.sourceforge.net/packages/bison.htm)
3. [GCC](https://sourceforge.net/projects/mingw/files/)
4. Siga el siguiente [instructivo](https://issuu.com/lilianachisaguano/docs/instalacion_de_flex__bison_y_mingw)

* Tanto para los binarios instalados flex y bison, es recomendable instalarlos en C:\GnuWin32 y luego agregar "C:\GnuWin32\bin" en variables de entorno -> variables del sistema -> editar variable path y agregar a la lista.
* Lo mismo para gcc, agregar el path donde sea instalado (ej: C:\MinGW\bin) a las variables del sistema en la variable path.

#### Ubuntu

1. Abra una terminal
2. Ejecute los siguientes comandos:

```sudo apt-get update
sudo apt-get upgrade
sudo apt-get install flex
sudo apt-get install bison
sudo apt install gcc
```

3. Verifique la instalación ha sido exitosa ejecutándo los siguientes comandos

```
which flex
which bison
which gcc
```

#### Mac

1. Abra una terminal
2. Ejecute los siguientes comandos:

```sudo apt-get update
brew install flex
brew install bison
brew install gcc
```
3. Verifique la instalación ha sido exitosa ejecutándo los siguientes comandos

```
which flex
which bison
which gcc
```

### Ejecución  

#### Windows

Ejecutar el archivo run.bat

#### Linux / Unix

Ejecutar el archivo run.sh
