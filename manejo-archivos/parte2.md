# Manejo de archivos (parte 2 de 2)

En esta segunda parte se presentan técnicas más seguras y avanzadas para trabajar con archivos y directorios. Python ofrece herramientas que facilitan la gestión automática de recursos y la manipulación del sistema de archivos.

---

## Uso recomendado de `with open()`

La estructura `with open()` permite abrir archivos asegurando su cierre automático, incluso si ocurre un error durante la ejecución.

```python
with open("archivo.txt", "r") as f:
    contenido = f.read()
```

Este enfoque es preferible a usar `open()` junto con `close()` de forma manual.

---

## Métodos y funciones adicionales

| Función / Método | Descripción | Ejemplo de uso |
|------------------|-------------|----------------|
| `with open()` | Abre un archivo con cierre automático | `with open("archivo.txt") as f:` |
| `seek()` | Mueve el cursor a una posición específica | `archivo.seek(0)` |
| `tell()` | Devuelve la posición actual del cursor | `pos = archivo.tell()` |
| `truncate()` | Recorta el archivo a un tamaño definido | `archivo.truncate(50)` |
| `exists()` | Comprueba si un archivo existe | `os.path.exists("archivo.txt")` |
| `remove()` | Elimina un archivo | `os.remove("archivo.txt")` |
| `rename()` | Renombra un archivo | `os.rename("viejo.txt", "nuevo.txt")` |
| `mkdir()` | Crea un directorio | `os.mkdir("nueva_carpeta")` |
| `rmdir()` | Elimina un directorio vacío | `os.rmdir("nueva_carpeta")` |
| `listdir()` | Lista los archivos de un directorio | `os.listdir("ruta")` |

---

Utilizar correctamente estas funciones permite gestionar archivos y directorios de forma segura, evitando errores comunes y posibles fugas de memoria.