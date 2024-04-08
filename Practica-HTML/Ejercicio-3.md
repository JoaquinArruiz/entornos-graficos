# Ejercitación 3 - Cuestionario

a.

```
<a href="http://www.google.com.ar">Click aquí para ir a Google</a>
<a href="http://www.google.com.ar" target="_blank">Click aquí para ir a Google</a>
<a href="http://www. google.com.ar" type="text/html" hreflang="es" charset="utf-8" rel="help">
<a href="#">Click aquí para ir a Google</a>
<a href="#arriba">Click aquí para volver arriba</a>
<a name="arriba" id="arriba"></a>
```

El primer hipervinculo abre google en la misma pestaña y muestra el stexto\
El segundo hipervinculo abre google en una pestaña nueva y muestra el texto\
El tercer hipervinculo no funciona porque tiene un espacio luego del www., ademas de que no se visualiza\
El cuarto hipervinculo te lleva a la misma web en la que estas y muestra el texto\
El quinto vinculo te lleva a la seccion #arriba en caso de que exista alguna y muestra el texto Click aquí para volver arriba\
El sexto es la declaracion de un sector en la pagina web no se visualiza nada

b.

```
<p><img src="im1.jpg" alt="imagen1" /><a href="http://www.google.com.ar">Click aquí</a></p>
<p><a href="http://www.google.com.ar"><img src="im1.jpg" alt="imagen1" /></a> Click aquí</p>
<p><a href="http://www.google.com.ar"><img src="im1.jpg" alt="ima
gen1" />Click aquí</a></p>
<p><a href="http://www.google.com.ar"><img src="im1.jpg" alt="imagen1" /></a> <a
href="http://www.google.com.ar">Click aquí</a></p>
```

El primer caso la imagen y el hipervinculo son elementos separados, se ven la imagen y el texto por separado\
El segundo caso la imagen esta dentro del hipervinculo, y separado del hipervinculo se ve el texto\
El tercer caso la imagen esta dentro del hipervinculo y el texto tambien, ambos son clickeables y llevan a la misma url\
El cuarto caso la imagen y el texto estan en dos hipervinculos separados, se visualizan los dos separados y llevan al mismo destino con distintos enlaces\

c.

```
<ul>
<li>xxx</li>
<li>yyy</li>
<li>zzz</li>
</ul>
```

```
<ol>
<li>xxx</li>
<li>yyy</li>
<li>zzz</li>
</ol>
```

```
<ol>
<li>xxx</li>
</ol>
<ol>
<li value="2">yyy</li>
</ol>
<ol>
<li
value="3">zzz</li>
</ol>
```

```
<blockquote>
<p>1. xxx<br />
2. yyy<br />
3. zzz</p>
</blockquote>
```

En el primer caso se visualiaza una lista desordenada que contiene

- xxx
- yyy
- zzz

En el segundo caso se visualiza una lista ordenada que contiene:

1. xxx
2. yyy
3. zzz

En el tercer caso se visualiza a cada elemento de la lista en en su propia lista ordenada. El atributo value en las etiquetas li establece el número de inicio de cada elemento

<ol><li>xxx</li></ol>
<ol><li value="2">yyy</li></ol>
<ol><li value="3">zzz</li></ol>

En el cuarto caso se visualiza una cita con una lista de los elementos ordenados, se utiliza `<br/>`para el salto de linea.

<blockquote>
<p>1. xxx<br />
2. yyy<br />
3. zzz</p>
</blockquote>

d.

```
<table border="1" width="300">
<tr>
<th>Columna 1</th>
<th>Columna 2</th>
</tr>
<tr>
<td>Celda 1</td>
<td>Celda 2</td>
</tr>
<tr>
<td>Celda 3</td>
<td>Celda 4</td>
</tr>
</table>
```

```
<table border="1" width="300">
<tr>
<td><div align="center"><strong>Colum
na1</strong></div></td>
<td><div align="center"><strong>Columna
2</strong></div></td>
</tr>
<tr>
<td>Celda 1</td>
<td>Celda 2</td>
</tr>
<tr>
<td>Celda 3</td>
<td>Celda 4</td>
</tr>
</table>
```

En el primer caso se visualiza una tabla, los encabezados estan marcados con la tag td que se utiliza para las celdas con los datos, los encabezados estan en negrita y centrados por el atributo align del div y por la tag strong

En el segundo caso los encabezados estan marcados con la tag th que tiene la funcionalidad de marcar los encabezados especificamente. El texto se muestra en negrita y centrado gracias a dicha tag.

e.

```
<table width="200">
<caption>
```

```
<table width="200">
<tr>
```

En el primer caso se visualiza una etiqueta de tabla que tiene una caption, aunque al estar vacia la caption no contiene titulo la tabla
En el segundo caso se crea una tabla y se agrega una fila con tr
