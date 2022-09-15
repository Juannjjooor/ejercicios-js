## Construye un triángulo

Crea una función llamada buildTriangle() que aceptará un argumento (anchura máxima del triángulo) y devolverá la representación de la cadena de un triángulo. 

Mira el ejemplo de salida a continuación.

```javacript
buildTriangle(10);

*
* *
* * *
* * * *
* * * * *
* * * * * *
* * * * * * *
* * * * * * * *
* * * * * * * * *
* * * * * * * * * *
```

Puedes usar la función makeLine() para empezar. La función toma una longitud de línea, y construye una línea de asteriscos y devuelve la línea junto a un saltro de línea (\n).

```javascript
function makeLine(length) {
    var line = "";
    for (var j = 1; j <= length; j++) {
        line += "* "
    }
    return line + "\n";
}
```

Necesitarás llamar a esta función **makeLine()** desde **buildTriangle()**.

[Back](../../readme.md)