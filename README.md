# Repo para EIEC - DevOps - UNIR

Este repositorio servirá para demostrar el uso de Git, GitHub y los flujos de trabajo colaborativos mediante Pull Requests en la asignatura de EIEC (UNIR).  

El proyecto consiste en ordenar una lista de palabras desde un archivo de texto, con opciones para eliminar duplicados y definir el orden de la lista.

> **Nota:** Los comandos del Makefile funcionarán en Linux y MacOS. En caso de usar Windows, necesitarás adaptarlos o utilizar una máquina virtual Linux.

---

## 📂 Estructura del proyecto
- main.py
- Makefile
- README.md
- words.txt

## Ejecución

python3 main.py <filename> <dup>
  filename: **ruta** al fichero que contiene la lista de palabras, una por línea
  dup: **yes|no**, yes para eliminar palabras duplicadas, no para mantener la lista
