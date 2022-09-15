# ¿Qué me pongo?

Si eres como yo, encontrar la camiseta de la talla correcta a veces puede ser un desafío. 

¿Qué talla uso? ¿Cuál es la diferencia entre S (pequeña), M (mediana) y L (grande)? Normalmente uso la L, pero ¿qué pasa si necesito una XL (extra grande)? 

Afortunadamente, nuestros amigos de Teespring han creado una tabla de tallas para facilitar las cosas.

![](what-i-do-wear.png)

## Instrucciones

Utiliza la tabla de tallas de arriba, crea una serie de expresiones lógicas que impriman la talla de una camiseta basada en las medidas de shirtWidth, shirtLength y shirtSleeve. Las tallas válidas incluyen S, M, L, XL, 2XL y 3XL. Por ejemplo, si...

```javascript
let shirtWidth = 23; // size L (large)
let shirtLength = 30; // size L (large)
let shirtSleeve = 8.71; // size L (large)
```

Entonces imprime la __L__ en la consola.

**Hint**: Necesitarás comparar un rango de valores cuando compruebes el ancho, largo y manga de la camisa. Por ejemplo, si el ancho de la camisa es de al menos 20", pero no más de 22", entonces la camiseta debe ser mediana (M) - siempre y cuando los otros valores para la longitud y la manga de la camisa

Si la shirtWidth, shirtLength y shirtSleeve no se ajustan al rango de valores aceptables para una talla específica, entonces imprime __N/A__ en la consola. Por ejemplo, si...

```javascript
let shirtWidth = 18; // size S (small)
let shirtLength = 29; // size M (medium)
let shirtSleeve = 8.47; // size M (medium)
```

Entonces imprime **N/A** en la consola porque las medidas no coinciden con
un **tamaño** particular...

Si **shirtWidth** es igual a **19**, **shirtLength** es igual a **28** y **shirtSleeve** es igual a  **8.21**, entonces **S** debe ser impreso en la consola.

Si **shirtWidth** es igual a **26**, **shirtLength** es igual a **33** y **shirtSleeve** equals **9.63**, entonces **2XL** debe ser impreso en la consola.

Si **shirtWidth** es igual a **18**, **shirtLength** es igual a **29** y **shirtSleeve** es igual a **8.47**, entonces **N/A** debe ser impreso en la consola.

### Tu código

```javascript

let shirtWidth = 23;
let shirtLength = 30;
let shirtSleeve = 8.71;

// your code goes here
```

[Back](../../readme.md)