## Reto #4 - P30

### Descripción

El chef de la pizzeria “Mominos” sale todas las mañanas a la plaza de
mercado a comprar los ingredientes para sus pizzas. Como él tiene una
lista con los ingredientes que le hacen falta, quieren saber los
ingredientes que puede comprar y el precio a pagar por dicha compra,
dada la disponibilidad de productos en la plaza.

### Tarea

Elaborar un programa que permita, dada la disponibilidad de productos
que tiene la plaza de mercado y la lista de ingredientes que le faltan
al chef, conocer los ingredientes que compro y el precio total que pago
por su compra.

### Entrada

Dos cadenas de caracteres. La primera cadena representa un diccionario
(en formato JSON) que tiene las parejas ingrediente:precio de todos los
ingredientes disponibles en la plaza de mercado, y la segunda representa
la lista de ingredientes (separados por espacio) que necesita el chef
para preparar sus pizzas.

### Salida

Dos cadenas de caracteres, que representan el precio total de los
ingredientes y los ingredientes (separados por espacio) que pudo
comprar.

----

### Ejemplo Entrada
```python
{ "t": 66, "u": 72, "d": 90, "r": 84, "j": 36, "g": 50, "s": 94, "q": 62, "f": 35 }

d p h u i e t q
```

### Ejemplo Salida
```python
290

d u t q
```
