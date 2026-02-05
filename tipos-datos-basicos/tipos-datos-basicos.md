# Tipos de datos básicos

Los tipos de datos constituyen la base de cualquier programa en Python, ya que definen **cómo se almacenan, representan y manipulan los valores** dentro del código. Comprenderlos permite escribir programas más claros, eficientes y fáciles de mantener.

Python incluye tanto **tipos de datos primitivos**, como números o cadenas de texto, como **estructuras de datos** más complejas que permiten organizar y manejar colecciones de información.

Conocer estas diferencias es fundamental para tomar buenas decisiones al momento de diseñar una solución.

---

## Tipos primitivos

| Nombre            | Palabra reservada | Ejemplo de sintaxis |
|------------------|------------------|--------------------|
| Entero           | `int`            | `0`                |
| Flotante         | `float`          | `3.14`             |
| Cadena de texto  | `str`            | `"Hola"`           |
| Booleano         | `bool`           | `True` / `False`   |
| Complejo         | `complex`        | `1 + 2j`           |
| Byte             | `bytes`          | `b"Hola"`          |
| Nulo             | `NoneType`       | `None`             |

Los tipos primitivos representan valores simples y directos, y suelen utilizarse como bloques básicos dentro de estructuras más complejas.

---

## Estructuras de datos

| Nombre                | Palabra reservada | Ejemplo de sintaxis        |
|----------------------|------------------|----------------------------|
| Lista / Pila         | `list`           | `[1, 2, 3]`                |
| Tupla                | `tuple`          | `(1, 2, 3)`                |
| Conjunto             | `set`            | `{1, 2, 3}`                |
| Conjunto inmutable   | `frozenset`      | `frozenset({1, 2, 3})`     |
| Diccionario          | `dict`           | `{"clave": "valor"}`       |
| Bytearray            | `bytearray`      | `bytearray(5)`             |
| Rango                | `range`          | `range(5)`                 |
| Vista de memoria     | `memoryview`     | `memoryview(bytes(5))`     |

Las estructuras de datos permiten almacenar y organizar múltiples valores, facilitando operaciones como búsquedas, iteraciones y transformaciones de información.


