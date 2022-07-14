# 📌 Checkpoint 1 - 29/04/2022

💡 Aquí se encuentran los detalles del progreso al momento de la presentación del checkpoint 1.

Al ser el primer checkpoint, se realizaron tareas básicas de setup y deployment generales para toda la aplicación.

---

## General

Estos puntos abarcan la totalidad de la app.

- Determinación de tecnologías a utilizar.
- Creación de repos.
- Determinación de bases de datos a utilizar.
- Deploys: CI / CD para deploys en Heroku ya que al momento de comenzar el proveedor había deshabilitado la integración plena con repositorios de Github para deploys por -_yet another_- [incidente con leaks de passwords](https://status.heroku.com/incidents/2413).
- Encontrarse y adaptarse a la elección de Github Actions.
- Establecer flujo de trabajo mediante **Feature branches**.
- Configuración general para usuarios con Firebase.

---

## Frontend: Admin

En esta primera etapa se realizó la creación y deploy del frontend de admin.

- Elección de template para la web.
- Login con email y contraseña mediante Firebase.
- Registro de admins.
- Login de admins.
- Listado de usuarios del sistema con datos mockeados.
- Creación de usuarios.

---

## Frontend: Mobile

En esta primera etapa se realizó la creación y deploy del frontend.

- Login con email y contraseña mediante Firebase.

---

## Backend: Users & Media

Como en la totalidad de la app, en esta primera etapa se realizó la creación, dockerización y deploy del backend.

- Creación de ambos repos.
- Dockerización completa de apps.
- Deploys mediante Github Actions.
- Tests mediante docker emulando una BDD para esta tarea.
