# Git y GitHub

Estos son los comandos que utilizaremos durante todas las clases para guardar nuestros proyectos en GitHub.

---

## 1. Ver el estado del proyecto

´´´bash
git status
´´´

Muestra los archivos que fueron modificados.

---

## 2. Agregar los cambios 

´´´bash
git add .
´´´

Agrega todos los archivos modificados.

> El punto (´.´)significa **todos los archivos**.

---

## 3. Crear un commit

´´´bash
git commit -m "Descripcion de los cambios"
´´´


Guarda una nueva version del proyecto.

> 

## 4. Subir el proyecto a GitHub 

´´´bash
git push origin main .
´´´


sube el proyecto a GitHub.

- "origin" -> Repositorio remoto.
- "Main" -> Rama priocipal.

---

# Flujo de trabajo

´´´bash
git status
git add .
git commit -m "Descripcion de los cambios"
git push origin main
´´´

> 💡 **Recordá:** cada vez que termines una actividad , realiza un **commit** y subi tu proyecto a Github.