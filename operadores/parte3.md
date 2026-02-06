# Operadores (parte 3 de 3)

En esta última parte se abordan operadores más específicos de Python: **identidad**, **pertenencia**, **bitwise**, así como operadores especiales como el **condicional ternario** y el **operador walrus**. Aunque algunos se usan con menor frecuencia, conocerlos aporta un mayor dominio del lenguaje.

---

## Operadores de identidad

Permiten comprobar si dos variables hacen referencia al **mismo objeto en memoria**, no solo si tienen el mismo valor.

| Nombre  | Representación | Ejemplo de uso |
|-------|----------------|---------------|
| Es    | `is`           | `a is b`      |
| No es | `is not`       | `a is not b`  |

---

## Operadores de pertenencia

Se utilizan para verificar si un elemento forma parte de una colección.

| Nombre           | Representación | Ejemplo de uso     |
|------------------|----------------|-------------------|
| Pertenece        | `in`           | `x in lista`      |
| No pertenece     | `not in`       | `x not in lista`  |

---

## Operadores bit a bit (bitwise)

Trabajan directamente sobre la representación binaria de los valores.

| Nombre                   | Representación | Ejemplo de uso |
|--------------------------|----------------|---------------|
| AND bit a bit            | `&`            | `a & b`       |
| OR bit a bit             | `|`            | `a | b`       |
| XOR bit a bit            | `^`            | `a ^ b`       |
| NOT bit a bit            | `~`            | `~a`          |
| Desplazamiento a la izq. | `<<`           | `a << n`      |
| Desplazamiento a la der. | `>>`           | `a >> n`      |

---

## Operador condicional ternario

Permite escribir una condición en una sola línea.

```python
x if condicion else y
```

## Operador walrus

El operador walrus (:=) permite asignar un valor a una variable dentro de una expresión.

```python
(x := valor)
```

Con esto se completa el bloque de operadores, proporcionando una visión completa de las distintas formas de trabajar con expresiones en Python.

