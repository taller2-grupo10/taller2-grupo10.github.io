# Checkpoint 4 - Entrega Final - 08/07/2022

## Frontend: Admin

- Mejoras de UI con mayor información.
- Listado de transacciones.
- Visualización de perfil de usuario.
- Bloqueo de contenido.
- Sección de servicios que permite listado, visualización, alta y bloqueo.
- Vista de métricas de usuario.

---

## Frontend: Mobile

- Mejoras de UX y UI: se rehicieron la mayoría de las pantallas desde cero en cuanto a UI y en gran parte UX.
- Reproducción global en la app.
- Pequeña mejora de UI del chat
- Queue de canciones completamente funcional.
- Pantallas de listado de canciones de playlist.
- Login de usuarios con proveedores de identidad federada. (Google)
- Pantalla de Home con recomendaciones basadas en ubicación y géneros.
- Swap de pantallas de perfil y library, para que el usuario pueda editar su contenido en su perfil y reproducirlo en su library.
- Búsquedas por suscripción.
- Mayor detalle en la información que se muestra en las distintas pantallas.

---

## Backend: Users, Media, Payments, API

- Deploy y CI completo con dockerización de backend de API para servicios con base de datos relacional en Postgres.
- Se realizaron tests para todos los nuevos endpoints de `media-be`.
- Se agregaron tests que cubren casi la totalidad de la funcionalidad de `payments-be`.
- Se agregó documentación faltante de Swagger para todos los backends.
- Búsquedas por suscripción.
- Endpoints para contenido para admins, permitiendo bloquear/desbloquear contenido (albums, playlists, canciones).
- Realización de métricas de usuario, mediante datos provistos por firebase y uso de información almacenada específicamente en tablas para este caso.
- Colaboración en playlists.
- Implementación de API key del servicio principal de la app, medio por el cual se comunican los servicios de la app.
- Se corrigió un problema que ocurría con Firebase al momento de subir archivos a Firebase Storage desde `media-be`, esto generaba que en múltiples ocasiones no se lograran subir archivos y se generase un timeout.
  La solución fue subir el archivo en `users-be` para que luego `media-be` pueda obtener su link, evitando así el timeout y enviar archivos potencialmente grandes a través de dos backends. Esto permite la subida más rápida de archivos ya que solo se realiza "un viaje".
