# TUTORIAL MARKDOWN

## ¿Qué es Markdown?

Markdown fue desarrollado en 2004 por John Gruber, y se refiere a una manera de formar archivos de texto que sirvan para documentar procesos. Su sintaxis simple se aprende rápidamente y es altamente legible en el mismo documento y cuando se transforma en HTML u otro tipo de documentos.

## Sintaxis en Markdown

Los archivos en Markdown se guardan con la extensión ***.md*** y se pueden abrir con cualquier editor como Visual studio code, TextEdit, Notepad, Sublime Text o Vim, entre otros.

### Encabezados

Markdown dispone de cuatro niveles de encabezados definidos por el símbolo de ***#*** antes del texto del encabezado. A continuación vemos los ejemplos de encabezados:

```
# Encabezado de primer nivel o h1.
## Encabezado de segundo nivel o h2.
### Encabezado de tercer nivel o h3.
#### Encabezado de cuarto nivel o h4.
```

Visualización:

# Encabezado de primer nivel o h1.
## Encabezado de segundo nivel o h2.
### Encabezado de tercer nivel o h3.
#### Encabezado de cuarto nivel o h4.

___

### Párrafos

Los párrafos deben estar separados por una línea vacía. Los saltos de línea sencillos se pueden generar dejando dos espacios al finalizar el primer texto. Ejemplo:

```
Este es un párrafo.  
Este es otro párrafo.  
```
Visualización:

Este es un párrafo.  
Este es otro párrafo.  

---

### Añadir énfasis

El texto se puede poner en cursivas encerrándolo entre los símbolos * o -. De la misma forma, el texto en negritas se escribe encerrando la palabra entre ** o __. Ejemplo:

```
*Este es un texto en cursiva con asterísco*  
_Este es otro texto en cursiva con línea abajo_

**Este es un texto en negrilla con dos asteriscos**
__Este es otro texto en negrilla con dos líneas abajo seguidas__
```

Visualización:

*Este es un texto en cursiva con asterísco*  
_Este es otro texto en cursiva con línea abajo_

**Este es un texto en negrilla con dos asteriscos**  
__Este es otro texto en negrilla con dos líneas abajo seguidas__

***

### Listas

Markdown soporta la creación de listas ordenadas y sin ordenar. Poner sangría al * permite crear listas anidadas. Ejemplos:

```
* Frutas
	* Manzanas
  	* Naranjas
  	* Uvas
* Lácteos
  	* Leche
  	* Queso
```

Visualización:

* Frutas
	* Manzanas
  	* Naranjas
  	* Uvas
* Lácteos
  	* Leche
  	* Queso

Las listas ordenadas se escriben numerando cada línea. Ejemplo:

```
1. Terminar el tutorial de Markdown
2. Ir a la tienda de abarrotes
3. Preparar el almuerzo
```

Visualización:

1. Terminar el tutorial de Markdown
2. Ir a la tienda de abarrotes
3. Preparar el almuerzo

___

### Fragmentos de código

Para representar fragmentos de código se utilizan tres signos de acento grave o tildes invertidas. También se pude escribir parte de código dentro de un párrafo utilizando una sola tilde invertida. Ejemplo:

```
Esto es parte de `codigo de javascript`.
```

Visualización:

Esto es parte de `codigo de javascript`.

Visualización:

```php
<?php
	echo "Prueba";
?>
```

---

### Textos en bloque

Para colocar textos en bloque se utliza el símbolo: *>*. Ejemplo:

```
> Éste es un párrafo de texto incluido en un bloque de cita. 
```

Visualización:

> Éste es un párrafo de texto incluido en un bloque de cita. 

***

### Links o enlaces de internet

Para colocar enlaces hacia sitios de internet se puede realizar de dos maneras:

1. El título del enlace se encierra primero entre corchetes y después se incluye la dirección completa del URL entre paréntesis. Ejemplo:

	```
	Este es un link al sitio [Google.com](https://google.com)
	```

	Visualización:

	Este es un link al sitio [Google.com](https://google.com)

2. Se puede colocar el link directamente con la ruta hacia el sitio web sin colocar el título del enlace. Estos son los llamados Autolinks. Ejemplo:

	```
	Enlace a google <https://google.com>
	```

	Visualización:

	Enlace a google <https://google.com>

___

### Imágenes

Se pueden incluir imágenes mediante el uso del signo de admiración **!** seguido de un texto alternativo entre paréntesis **()** y luego a su vez por el URL de la imagen y un título opcional entre comillas **""**. 

```
	![Logo de Google](https://www.google.com.co/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "Google logo")
```

Visualización:

![Logo de Google](https://www.google.com.co/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "Google logo")

***

### Líneas horizontales o Breaks

Para incluir líneas horizontales en una misma línea se utilizan cualquiera de los siguientes tres signos: `___, ---, o ***`. Ejemplos:

```
___  

---  

***
```

Visualización:
___  

---  

***

### Tablas

Para crear una tabla en Markdown se usan barras verticales o pipe | para separar columnas y guiones entre los encabezados y el resto del contenido de la tabla. 

```
| Encabezado 1 | Encabezado 2 | Encabezado 3 |
| --------- | --------- | --------- |
| renglón 1, columna 1 | renglón 1, columna 2 | renglón 1, columna 3|
| renglón 2, columna 1 | renglón 2, columna 2 | renglón 2, columna 3|
| renglón 3, columna 1 | renglón 3, columna 2 | renglón 3, columna 3|
```

Visualización:

| Encabezado 1 | Encabezado 2 | Encabezado 3 |
| --------- | --------- | --------- |
| renglón 1, columna 1 | renglón 1, columna 2 | renglón 1, columna 3|
| renglón 2, columna 1 | renglón 2, columna 2 | renglón 2, columna 3|
| renglón 3, columna 1 | renglón 3, columna 2 | renglón 3, columna 3|

Para alinear el contenido de cada columna se pueden agregar el signo de dos puntos **:** al renglón de los encabezados. Ejemplo:

```
| Alineado-izquierda | Centrado | Alineado-derecha |
| :-------- | :-------: | --------: |
| Casas | rojo | 10 |
| Carros | amarillo | 25 |
| Motos | azul | 10 |
```

Visualización:

| Alineado-izquierda | Centrado | Alineado-derecha |
| :-------- | :-------: | --------: |
| Casas | rojo | 10 |
| Carros | amarillo | 25 |
| Motos | azul | 10 |


