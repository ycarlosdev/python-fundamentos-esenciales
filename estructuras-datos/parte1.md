# Estructuras de datos (parte 1 de 3)

Las **listas**, **tuplas**, **conjuntos** y **diccionarios** son estructuras de datos esenciales en Python. Cada una ofrece métodos específicos que permiten **almacenar, modificar y consultar información** de forma eficiente.  
En esta primera parte se presentan los métodos más comunes para trabajar con **listas** y **tuplas**.

---

## Listas (`list`)

Las listas son colecciones **ordenadas y mutables**, lo que permite modificar su contenido después de ser creadas.

| Método | Descripción | Ejemplo de uso |
|------|-------------|---------------|
| `append()` | Añade un elemento al final de la lista | `lista.append(valor)` |
| `extend()` | Agrega múltiples elementos desde un iterable | `lista.extend(iterable)` |
| `insert()` | Inserta un elemento en una posición específica | `lista.insert(i, valor)` |
| `remove()` | Elimina la primera aparición de un valor | `lista.remove(valor)` |
| `pop()` | Elimina y devuelve un elemento (por índice o el último) | `lista.pop(i)` / `lista.pop()` |
| `index()` | Devuelve el índice de un valor | `lista.index(valor)` |
| `count()` | Cuenta cuántas veces aparece un valor | `lista.count(valor)` |
| `sort()` | Ordena los elementos de la lista | `lista.sort()` |
| `reverse()` | Invierte el orden de la lista | `lista.reverse()` |
| `copy()` | Crea una copia superficial de la lista | `lista.copy()` |
| `clear()` | Elimina todos los elementos de la lista | `lista.clear()` |

---

## Tuplas (`tuple`)

Las tuplas son colecciones **ordenadas e inmutables**, lo que las hace útiles cuando los datos no deben modificarse.

| Método | Descripción | Ejemplo de uso |
|------|-------------|---------------|
| `count()` | Cuenta las ocurrencias de un valor | `tupla.count(valor)` |
| `index()` | Devuelve el índice de un valor | `tupla.index(valor)` |

---

Estas estructuras permiten organizar y manipular datos de forma clara, y su correcto uso es clave para escribir código eficiente en Python.
