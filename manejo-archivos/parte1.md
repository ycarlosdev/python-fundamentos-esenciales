# Manejo de archivos (parte 1 de 2)

El manejo de archivos es una tarea muy común en programación. Python permite **leer, escribir, modificar y cerrar archivos** de forma sencilla mediante funciones integradas como `open()`, junto con distintos métodos de lectura y escritura.  
Además, ofrece soporte para trabajar con archivos de texto y binarios de manera eficiente.

---

## Modos de apertura con `open()`

Al abrir un archivo, es posible indicar el modo de acceso:

- `"r"` → Lectura (modo por defecto)
- `"w"` → Escritura (sobrescribe el contenido existente)
- `"a"` → Agrega contenido al final del archivo
- `"rb"` / `"wb"` → Lectura y escritura en modo binario

---

## Funciones y métodos principales

| Función / Método | Descripción | Ejemplo de uso |
|-----------------|-------------|---------------|
| `open()` | Abre un archivo en el modo indicado | `archivo = open("archivo.txt", "r")` |
| `read()` | Lee todo el contenido del archivo | `contenido = archivo.read()` |
| `readline()` | Lee una única línea del archivo | `linea = archivo.readline()` |
| `readlines()` | Lee todas las líneas y las devuelve en una lista | `lineas = archivo.readlines()` |
| `write()` | Escribe datos en el archivo | `archivo.write("Texto")` |
| `writelines()` | Escribe múltiples líneas en el archivo | `archivo.writelines(lista_texto)` |
| `close()` | Cierra el archivo y libera recursos | `archivo.close()` |
| `flush()` | Fuerza la escritura del buffer en el archivo | `archivo.flush()` |

---

Un manejo adecuado de archivos es esencial para trabajar con datos persistentes y garantizar que los recursos del sistema se utilicen correctamente.