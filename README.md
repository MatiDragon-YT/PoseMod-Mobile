# PoseMod Mobile
Port de PC para Android

**Requiere**
+ CLEO4
+ CLEO+
+ AML (Android)

**Como funciona internamente?**<br>
<br>
En teoria, deberia de bastar con tener un Pointer a la Matrix de los huesos.

> * Un **Pointer** es un numero que representa la direccion de donde se guarda algo en la memoria RAM.
> * Una **Matrix** no es mas que un Array que almacena las coordenadas, angulo y escala de un elemento 3D.

De esta forma bastaria con solo leer o escribir estos punteros para hacer que algo se mueva a un determinado lugar.
