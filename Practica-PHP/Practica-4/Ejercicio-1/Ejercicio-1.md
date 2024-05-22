# Ejercicio 1:
**En el siguiente código identificar:**


• las variables y su tipo

• los operadores

• las funciones y sus parámetros

• las estructuras de control

• cuál es la salida por pantalla**
```
<?php
function doble($i) {
return $i*2;
}
$a = TRUE;
$b = "xyz";
$c = 'xyz';
$d = 12;
echo gettype($a);
echo gettype($b);
echo gettype($c);
echo gettype($d);
if (is_int($d)) {
$d += 4;
}
if (is_string($a)) {
echo "Cadena: $a";
}
$d = $a ? ++$d : $d*3;
$f = doble($d++);
$g = $f += 10;
echo $a, $b, $c, $d, $f , $g;
?>
```

**Variables:**
a (boolean)
b (string)
c (string)
d (int)
f (int)
g (int)
i (float)

**Operadores**
``` * = += ?: ++```

**Funciones**
```
doble (float)

echo (string)

gettype ($a)

is_int ($d)

is_string ($a)
```

**Estructura de Control**
```
if {}
```
**Salida por Pantalla**

booleanstringstringinteger1xyzxyz184444
