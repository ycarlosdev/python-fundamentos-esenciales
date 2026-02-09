# Manejo de archivos (parte 2 de 2)

En esta segunda parte se presentan técnicas más seguras y avanzadas para trabajar con archivos y directorios. Python ofrece herramientas que facilitan la gestión automática de recursos y la manipulación del sistema de archivos.

---

## Uso recomendado de `with open()`

La estructura `with open()` permite abrir archivos asegurando su cierre automático, incluso si ocurre un error durante la ejecución.

```python
with open("archivo.txt", "r") as f:
    contenido = f.read()