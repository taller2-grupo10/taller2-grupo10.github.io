# Checkpoint 3 - 17/06/2022 → 24/06/2022

💡 Aquí se encuentran los detalles del progreso al momento de la presentación del checkpoint 3.

### 📄 [Presentación en Google Slides](https://docs.google.com/presentation/d/1RTpt09JcYum2nEIl4dF9JB5yzEvXA9movpVSvnVenlA/edit?usp=sharing)

---

## General

Estos puntos abarcan la totalidad de la app.

- Chat funcional con búsqueda de artistas para ingresar a su chat respectivo.
  Pendiente: UI, mejorar.
- Playlists:
  - Pendientes del checkpoint anterior: crear/editar.
  - Colaboración en playlists.
- Notificaciones, tanto para mensaje como para otros casos como adición de colaborador a playlist.
- Login de usuarios con identidad federada: Google.
- Login con datos biométricos prometido, queda pendiente.
- Recupero de contraseña.

---

## Frontend: Admin

- Listar usuarios del sistema.
- Visualizar perfil de usuario.
- Bloquear/habilitar usuario/artista.
- Bocetado de métricas, aún sin finalizar.

---

## Frontend: Mobile

- Edición de perfil.
- Búsquedas por artista completadas.
- Edición de álbum.
- Consulta de saldo restante en la wallet del usuario.
- Ciertas mejoras de UX y UI.
- Reproducción global en la app. (WIP)
- Queue de canciones, pudiendo avanzar y retroceder.
- Inscripcion a suscripción.

---

## Backend: Users & Media & Payments

- Deploy completo con dockerización de backend de Payments.
- Armado de base de datos para persistencia con Postgres de Heroku.
- Armado de operaciones generales de pagos con smart contract.
- Creación de wallet al registrar usuario.
- Envío de notificaciones mediante Expo.
- Inscripción y modificación de suscripción: adición de tablas y suscripciones, habilitación de pagos (deposit).
