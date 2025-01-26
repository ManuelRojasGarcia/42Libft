# 42Libft

Este repositorio contiene la implementación de la biblioteca estándar de C como parte del proyecto **Libft** de la escuela 42. El objetivo es desarrollar una librería personalizada con funciones esenciales de manipulación de cadenas, memoria y conversiones numéricas, siguiendo buenas prácticas de codificación y estructuración.

## 📂 Contenido del repositorio

### 🗂️ Archivos principales:

- **📄 libft.h**: Archivo de cabecera con las declaraciones de funciones.
- **⚙️ Makefile**: Script para compilar la librería.
- **📝 src/**: Directorio con implementaciones de funciones en C.

### 🛠️ Funciones implementadas:

#### Manipulación de cadenas:
- `ft_strlen`: Calcula la longitud de una cadena.
- `ft_strcpy`: Copia una cadena.
- `ft_strcmp`: Compara dos cadenas.

#### Manipulación de memoria:
- `ft_memset`: Rellena un bloque de memoria con un valor.
- `ft_memcpy`: Copia bloques de memoria.
- `ft_memmove`: Mueve bloques de memoria.

#### Conversión de datos:
- `ft_atoi`: Convierte una cadena a un número entero.
- `ft_itoa`: Convierte un número entero a cadena.

## ⚙️ Compilación

Para compilar la biblioteca, ejecutar el siguiente comando:

```sh
make
```

Esto generará el archivo `libft.a` para su uso en otros proyectos.

## 🚀 Uso

Para utilizar la biblioteca en tus proyectos, incluye el encabezado y enlaza la librería:

```c
#include "libft.h"
```

Compilar el proyecto con:

```sh
gcc main.c -L. -lft -o my_program
```

## 📧 Contacto

Autor: **Manuel Rojas Garcia**  
Repositorio: [42Libft](https://github.com/ManuelRojasGarcia/42Libft)

