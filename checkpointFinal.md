# 馃搶 Checkpoint 4 - Entrega Final - 08/07/2022

## Frontend: Admin

- Mejoras de UI con mayor informaci贸n.
- Listado de transacciones.
- Visualizaci贸n de perfil de usuario.
- Bloqueo de contenido.
- Secci贸n de servicios que permite listado, visualizaci贸n, alta y bloqueo.
- Vista de m茅tricas de usuario.

---

## Frontend: Mobile

- Mejoras de UX y UI: se rehicieron la mayor铆a de las pantallas desde cero en cuanto a UI y en gran parte UX.
- Reproducci贸n global en la app.
- Peque帽a mejora de UI del chat
- Queue de canciones completamente funcional.
- Pantallas de listado de canciones de playlist.
- Login de usuarios con proveedores de identidad federada. (Google)
- Pantalla de Home con recomendaciones basadas en ubicaci贸n y g茅neros.
- Swap de pantallas de perfil y library, para que el usuario pueda editar su contenido en su perfil y reproducirlo en su library.
- B煤squedas por suscripci贸n.
- Mayor detalle en la informaci贸n que se muestra en las distintas pantallas.

---

## Backend: Users, Media, Payments, API

- Deploy y CI completo con dockerizaci贸n de backend de API para servicios con base de datos relacional en Postgres.
- Se realizaron tests para todos los nuevos endpoints de `media-be`.
- Se agregaron tests que cubren casi la totalidad de la funcionalidad de `payments-be`.
- Se agreg贸 documentaci贸n faltante de Swagger para todos los backends.
- B煤squedas por suscripci贸n.
- Endpoints para contenido para admins, permitiendo bloquear/desbloquear contenido (albums, playlists, canciones).
- Realizaci贸n de m茅tricas de usuario, mediante datos provistos por firebase y uso de informaci贸n almacenada espec铆ficamente en tablas para este caso.
- Colaboraci贸n en playlists.
- Implementaci贸n de API key del servicio principal de la app, medio por el cual se comunican los servicios de la app.
- Se corrigi贸 un problema que ocurr铆a con Firebase al momento de subir archivos a Firebase Storage desde `media-be`, esto generaba que en m煤ltiples ocasiones no se lograran subir archivos y se generase un timeout.
  La soluci贸n fue subir el archivo en `users-be` para que luego `media-be` pueda obtener su link, evitando as铆 el timeout y enviar archivos potencialmente grandes a trav茅s de dos backends. Esto permite la subida m谩s r谩pida de archivos ya que solo se realiza "un viaje".
- Se agregan c贸digos de error gen茅ricos.