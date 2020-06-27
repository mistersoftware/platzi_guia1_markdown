
## ¿Qué es Markdown?

Markdown es una herramienta de conversión de texto a HTML para escritores web. Markdown le permite escribir utilizando un formato de texto sin formato fácil de leer y escribir, y luego convertirlo en XHTML (o HTML) estructuralmente válido.

Por lo tanto, “Markdown” es dos cosas:

1.  Una sintaxis de formato de texto sin formato
2.  Una herramienta de software, escrita en Perl, que convierte el formato de texto sin formato a HTML.

El objetivo primordial de diseño para la sintaxis de formato de Markdown es hacerlo lo más legible posible. La idea es que un documento con formato de Markdown se pueda publicar tal como está, como texto sin formato, sin que parezca que se haya marcado con etiquetas o instrucciones de formato. Si bien la sintaxis de Markdown ha sido influenciada por varios filtros de texto a HTML existentes, la mayor fuente de inspiración para la sintaxis de Markdown es el formato del correo electrónico de texto sin formato. Tomado de [Git-hub](https://guides.github.com/features/mastering-markdown/)

## Encabezados

```
## Esta es una etiqueta <h2> 

```

Produce:

## Esta es una etiqueta <h2>

## Etiquetas de Énfasis

```
*Este texto aparecerá en cursiva*
_Este texto también aparecerá en cursiva_
**Este texto aparecerá en negrilla**
__Este texto también aparecerá en negrilla__
~~Este texto aparecerá tachado~~
_También **puedes** combinarlos_

```

Producirá  
_Este texto aparecerá en cursiva_  
_Este texto también aparecerá en cursiva_  
**Este texto aparecerá en negrilla**  
**Este texto también aparecerá en negrilla**  
Este texto aparecerá tachado  
_También **puedes** combinarlos_

## Listas Ordenadas

```
1. Ítem 1
1. Ítem 2
1. Ítem 3
   1. Ítem 3a
   1. Ítem 3b

```

Producirá

1.  Ítem 1
2.  Ítem 2
3.  Ítem 3
    1.  Ítem 3a
    2.  Ítem 3b

## Listas No ordenadas

```
* Ítem 1
* Ítem 2
  * Ítem 2a
  * Ítem 2b

```

Producirá

-   Ítem 1
-   Ítem 2
    -   Ítem 2a
    -   Ítem 2b

## Imágenes

```
![Platzi logo]( https://static.platzi.com/static/css/logo.a76b2a87162b3b46529c30d1cb91ccc6.png)

```

Producira  
![Platzi logo](https://static.platzi.com/static/css/logo.a76b2a87162b3b46529c30d1cb91ccc6.png)  
El formato sigue la siguiente regla: Texto alternativo para la imagen entre corchetes cuadrados precedido por el símbolo de cierre de exclamación, seguido por la url donde se encuentra almacenada la imagen dentro de paréntesis.

## Enlaces

```
http://github.com – enlace creado de forma automática!
[Platzi](http://platzi.com)

```

Producirá  
[http://github.com](http://github.com) – enlace creado de forma automática!  
[Platzi](http://platzi.com)  
El formato sigue la siguiente regla: El texto alternativo para el enlace entre corchetes cuadrados seguido de la url dentro de paréntesis. Si deseas que el texto mostrado sea igual al de la url solo debes escribir la url y será convertida automáticamente.

## Citas

```
Como el famoso filosofo moderno Daddy Yanky dijo:
> Lo que paso
> Paso.

```

Producirá  
Como el famoso filosofo moderno Daddy Yanky dijo:

> Lo que paso  
> Paso.

## Resaltado de sintaxis para código

```
\````javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
\````

```

Producirá

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}

```

## Listas de tareas

```
- [x] Tarea  realizada
- [x] Otra tarea realizada sin ordenar
- [ ] Tarea sin realizar

```

Producirá

-   [x] Tarea realizada
-   [x] Otra tarea realizada sin ordenar
-   [ ] Tarea sin realizar

## Tablas

```
Primer Encabezado | Segundo Encabezado
------------ | -------------
Contenido de la columna 1 fila 1 | Contenido de la columna 2 fila 1
Contenido de la columna 1 fila 2 | Contenido de la columna 2 fila 2
Contenido de la columna 1 fila 3 | Contenido de la columna 2 fila 3


```

Producirá

Primer Encabezado

Segundo Encabezado

Contenido de la columna 1 fila 1

Contenido de la columna 2 fila 1

Contenido de la columna 1 fila 2

Contenido de la columna 2 fila 2

Contenido de la columna 1 fila 3

Contenido de la columna 2 fila 3

## Emojis

```
:kissing:
:laughing:

```

Producirá  
😗  
😆

Aquí puedes ver un listado completo de [emojis](https://github.com/ikatyang/emoji-cheatsheet/blob/master/README.md) (no todos están soportados)

si necesitas escapar caracteres puedes hacerlo usando  
por ejemplo

```
- [ ] \(Si vas a incluir paréntesis después de corchetes cuadrados) será necesario escapar el primer paréntesis

```

Producirá

-   [ ] (Si vas a incluir paréntesis después de corchetes cuadrados) será necesario escapar el primer paréntesis

## Youtube

```
'@[youtube]( m_lEJyoWafo|https://www.youtube.com/watch?v=m_lEJyoWafo)'

```

Producirá  
’

formato es el siguiente @ [youtube] (id del video | url del video)

[https://www.youtube.com/watch?v=WMnASdda1w4](https://www.youtube.com/watch?v=WMnASdda1w4)  

