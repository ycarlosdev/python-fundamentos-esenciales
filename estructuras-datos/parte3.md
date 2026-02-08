# Estructuras de datos (parte 3 de 3)

En esta última parte se trabajan los **diccionarios**, una de las estructuras más potentes de Python. Permiten almacenar información en forma de **pares clave-valor**, facilitando el acceso, la actualización y la organización de datos de manera eficiente.

---

## Diccionarios (`dict`)

Los diccionarios son colecciones **no ordenadas (conceptualmente)** y **mutables**, ideales para representar datos relacionados mediante claves únicas.

| Método | Descripción | Ejemplo de uso |
|------|-------------|---------------|
| `keys()` | Devuelve todas las claves del diccionario | `diccionario.keys()` |
| `values()` | Devuelve los valores del diccionario | `diccionario.values()` |
| `items()` | Devuelve los pares clave-valor | `diccionario.items()` |
| `get()` | Obtiene el valor de una clave sin lanzar error | `diccionario.get(clave, defecto)` |
| `pop()` | Elimina y devuelve el valor asociado a una clave | `diccionario.pop(clave)` |
| `popitem()` | Elimina y devuelve el último par clave-valor | `diccionario.popitem()` |
| `update()` | Agrega o actualiza claves con nuevos valores | `diccionario.update(otro_dict)` |
| `setdefault()` | Obtiene un valor o lo asigna si no existe | `diccionario.setdefault(clave, valor)` |
| `copy()` | Crea una copia superficial del diccionario | `diccionario.copy()` |
| `clear()` | Elimina todos los elementos del diccionario | `diccionario.clear()` |

---

El uso correcto de diccionarios permite construir estructuras de datos claras y eficientes, especialmente en aplicaciones que manejan información estructurada.
