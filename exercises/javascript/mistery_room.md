En este misterio de asesinato hay:

- Cuatro salas: el **salón de baile**, la **galería**, la **sala de billar** y el **comedor**
- Cuatro armas: **veneno**, **un trofeo**, **un palo de billar** y un **cuchillo** 
- Cuatro sospechosos: El Sr. **Parkes**, la Sra. **Van Cleve**, la Sra. **Sparr** y el Sr. **Kaleho**.

También sabemos que cada arma corresponde a una sala en particular:

- El veneno pertenece al salón de baile
- El trofeo a la galería
- El palo de billar a la sala de billar
- El cuchillo al comedor.

Cada sospechoso fue localizado en una habitación específica en el momento del asesinato.

- El Sr. Parkes fue localizado en el comedor.
- La Sra. Van Cleve fue localizada en la galería.
- La Sra. Sparr estaba en la sala de billar.
- El Sr. Kalaho estaba en la sala de baile

Establezca el valor establecido del arma basado en la sala.
Ponga el valor de resuelto a verdadero si el valor de la habitación coincide con la habitación de los sospechosos

Ejemplo: Si la habitación es igual a la galería y los el sospechoso es igual a la Sra. Van Cleve, entonces la Sra. Van Cleve lo hizo en la galería con el trofeo.

```javascript
 let room;
 let suspect;
 let weapon = ''; 
 let solved = false; 

 // Your code here
 
 if (solved === true) {
    console.log(`ÈL asesino ha sido ${suspect}, lo hizo en la habitación ${room} y utilizo como arma ${weapon}`)
}
```

[Back](../../readme.md)