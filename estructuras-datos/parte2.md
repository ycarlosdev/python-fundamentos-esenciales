# Estructuras de datos (parte 2 de 3)

En esta parte se presentan los **conjuntos**, una estructura de datos muy útil cuando se trabaja con colecciones de elementos **únicos** y operaciones matemáticas como uniones e intersecciones.

---

## Conjuntos (`set`)

Los conjuntos son colecciones **no ordenadas y mutables** que no permiten elementos duplicados.

| Método | Descripción | Ejemplo de uso |
|------|-------------|---------------|
| `add()` | Agrega un elemento al conjunto | `conjunto.add(valor)` |
| `remove()` | Elimina un elemento (genera error si no existe) | `conjunto.remove(valor)` |
| `discard()` | Elimina un elemento sin generar error | `conjunto.discard(valor)` |
| `pop()` | Elimina y devuelve un elemento aleatorio | `conjunto.pop()` |
| `clear()` | Elimina todos los elementos del conjunto | `conjunto.clear()` |
| `union()` | Devuelve la unión de dos conjuntos | `conjunto.union(otro)` |
| `intersection()` | Obtiene los elementos comunes entre conjuntos | `conjunto.intersection(otro)` |
| `difference()` | Elementos que están en A pero no en B | `conjunto.difference(otro)` |
| `symmetric_difference()` | Elementos no comunes entre conjuntos | `conjunto.symmetric_difference(otro)` |

---

Los conjuntos resultan especialmente útiles para eliminar duplicados y realizar comparaciones rápidas entre colecciones de datos.
