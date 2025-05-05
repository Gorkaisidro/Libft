# Libft

Este proyecto consiste en la implementación de una librería personal en C, como parte del programa de la Escuela 42. Tiene como objetivo reforzar el conocimiento del lenguaje C, la gestión de memoria y las buenas prácticas de programación, recreando funciones de la librería estándar de C y desarrollando funciones adicionales.

---

## Tabla de Contenidos

- [Objetivo](#objetivo)
- [Funciones - Parte 1 (Libc)](#funciones---parte-1-libc)
- [Funciones - Parte 2 (Adicionales)](#funciones---parte-2-adicionales)
- [Funciones - Bonus (Listas enlazadas)](#funciones---bonus-listas-enlazadas)
- [Compilación](#compilación)
- [Uso](#uso)

---

## Objetivo

Recrear una serie de funciones de la librería estándar de C (`libc`), así como funciones adicionales útiles para proyectos posteriores, como la manipulación de cadenas y listas enlazadas.

---

## Funciones - Parte 1 (Libc)

| Función | Descripción |
|--------|-------------|
| `ft_isalpha` | Verifica si un carácter es alfabético. |
| `ft_isdigit` | Verifica si un carácter es un dígito decimal. |
| `ft_isalnum` | Verifica si un carácter es alfanumérico. |
| `ft_isascii` | Verifica si un carácter pertenece a la tabla ASCII. |
| `ft_isprint` | Verifica si un carácter es imprimible. |
| `ft_strlen` | Calcula la longitud de una cadena. |
| `ft_memset` | Rellena un bloque de memoria con un byte específico. |
| `ft_bzero` | Establece un bloque de memoria a cero. |
| `ft_memcpy` | Copia un bloque de memoria. |
| `ft_memmove` | Copia memoria permitiendo solapamiento entre origen y destino. |
| `ft_strlcpy` | Copia una cadena a un buffer limitado, devolviendo su longitud. |
| `ft_strlcat` | Concatena cadenas en un buffer limitado, devolviendo su longitud total. |
| `ft_toupper` | Convierte un carácter a mayúscula. |
| `ft_tolower` | Convierte un carácter a minúscula. |
| `ft_strchr` | Localiza la primera aparición de un carácter en una cadena. |
| `ft_strrchr` | Localiza la última aparición de un carácter en una cadena. |
| `ft_strncmp` | Compara hasta `n` caracteres entre dos cadenas. |
| `ft_memchr` | Busca un byte en un bloque de memoria. |
| `ft_memcmp` | Compara dos bloques de memoria. |
| `ft_strnstr` | Localiza una subcadena en otra cadena, con un tamaño limitado. |
| `ft_atoi` | Convierte una cadena a un entero (`int`). |
| `ft_calloc` | Asigna memoria inicializada a cero. |
| `ft_strdup` | Crea una copia duplicada de una cadena. |

---

## Funciones - Parte 2 (Adicionales)

| Función | Descripción |
|--------|-------------|
| `ft_substr` | Extrae una subcadena a partir de una cadena dada. |
| `ft_strjoin` | Concatena dos cadenas en una nueva. |
| `ft_strtrim` | Elimina caracteres especificados del principio y fin de una cadena. |
| `ft_split` | Divide una cadena según un delimitador y devuelve un array de subcadenas. |
| `ft_itoa` | Convierte un entero a una cadena (`string`). |
| `ft_strmapi` | Aplica una función a cada carácter de una cadena (con índice), y crea una nueva. |
| `ft_striteri` | Aplica una función a cada carácter de una cadena (con índice), modificándola in-place. |
| `ft_putchar_fd` | Escribe un carácter en un descriptor de archivo. |
| `ft_putstr_fd` | Escribe una cadena en un descriptor de archivo. |
| `ft_putendl_fd` | Escribe una cadena seguida de un salto de línea. |
| `ft_putnbr_fd` | Escribe un número entero en un descriptor de archivo. |

---

## Funciones - Bonus (Listas enlazadas)

Estas funciones permiten manipular listas enlazadas simples (estructura `t_list`):

| Función | Descripción |
|--------|-------------|
| `ft_lstnew` | Crea un nuevo nodo de lista con un contenido dado. |
| `ft_lstadd_front` | Añade un nuevo nodo al principio de la lista. |
| `ft_lstsize` | Devuelve el número de nodos de una lista. |
| `ft_lstlast` | Devuelve el último nodo de una lista. |
| `ft_lstadd_back` | Añade un nuevo nodo al final de la lista. |
| `ft_lstdelone` | Elimina un nodo, usando una función de eliminación para su contenido. |
| `ft_lstclear` | Elimina y libera todos los nodos de una lista. |
| `ft_lstiter` | Aplica una función a cada nodo de la lista. |
| `ft_lstmap` | Crea una nueva lista aplicando una función a cada nodo, con función de limpieza en caso de error. |

---

## Compilación

```bash
make
