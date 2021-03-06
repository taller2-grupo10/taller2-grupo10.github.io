# 馃搶 Checkpoint 1 - 29/04/2022

馃挕 Aqu铆 se encuentran los detalles del progreso al momento de la presentaci贸n del checkpoint 1.

Al ser el primer checkpoint, se realizaron tareas b谩sicas de setup y deployment generales para toda la aplicaci贸n.

---

## General

Estos puntos abarcan la totalidad de la app.

- Determinaci贸n de tecnolog铆as a utilizar.
- Creaci贸n de repos.
- Determinaci贸n de bases de datos a utilizar.
- Deploys: CI / CD para deploys en Heroku ya que al momento de comenzar el proveedor hab铆a deshabilitado la integraci贸n plena con repositorios de Github para deploys por -_yet another_- [incidente con leaks de passwords](https://status.heroku.com/incidents/2413).
- Encontrarse y adaptarse a la elecci贸n de Github Actions.
- Establecer flujo de trabajo mediante **Feature branches**.
- Configuraci贸n general para usuarios con Firebase.

---

## Frontend: Admin

En esta primera etapa se realiz贸 la creaci贸n y deploy del frontend de admin.

- Elecci贸n de template para la web.
- Login con email y contrase帽a mediante Firebase.
- Registro de admins.
- Login de admins.
- Listado de usuarios del sistema con datos mockeados.
- Creaci贸n de usuarios.

---

## Frontend: Mobile

En esta primera etapa se realiz贸 la creaci贸n y deploy del frontend.

- Login con email y contrase帽a mediante Firebase.

---

## Backend: Users & Media

Como en la totalidad de la app, en esta primera etapa se realiz贸 la creaci贸n, dockerizaci贸n y deploy del backend.

- Creaci贸n de ambos repos.
- Dockerizaci贸n completa de apps.
- Deploys mediante Github Actions.
- Tests mediante docker emulando una BDD para esta tarea.
