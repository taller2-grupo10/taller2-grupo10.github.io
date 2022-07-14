# Documentación de la aplicación mobile

<a href="https://expo.dev/artifacts/eas/xkLGa8dBjGr4n9iTBKqmDg.apk">
<img src="img/spotify-mobile.png" style="width:100px;"/>
</a>
<a href="https://github.com/taller2-grupo10/mobile-fe">
<img src="img/github-mobile-fe.png" style="width:100px;"/>
</a>

## Resumen

Esta es la aplicación principal de Spotifiuby, desarrollada para android. Esta cuenta con diferentes pantallas que nos permiten interactuar con la aplicación. Se pueden crear albunes, playlists y canciones, asi como escucharlas y buscarlas. También posee un sistema de suscripción con 4 tiers, que puede ser pagado a través de Ethereum. Se puede enviar mensajes a otros usuarios de la plataforma.

Para el desarrollo de ésta aplicación fue utilizado ReactNative en javascript, utilizando la biblioteca NativeBase ([NB](https://nativebase.io/)), y expo como proveedor de la aplicación, asi también como herramienta de exportación al formato apk ([EXPO](https://docs.expo.dev/))

---

## Registro

---

- Para registrarse es necesario proveer distintos datos, estos son, el nombre completo, email, contraseña, locación y generos de interes
- Snackbar para mostrar errores/cuando se ingresa correctamente
- Validación de campos (formato mail, contraseña segura, campos requeridos)
- Botón con estado cargando

<img src="img/mobile/sign_up.jpg" style="width:300px;" />
<img src="img/mobile/sign_up_completo.jpg" style="width:300px;" />

---

## Login

---

- Únicamente se podrá ingresar con un usuario ya registrado, utilizando su email y contraseña
- Snackbar para mostrar errores/cuando se ingresa correctamente
- Botón con estado cargando

<img src="img/mobile/sign_in.jpg" style="width:300px;" />
<img src="img/mobile/sign_in_completo.jpg" style="width:300px;" />
<img src="img/mobile/sign_in_loading.jpg" style="width:300px;" />

---

## Recupero de contraseña

---

- En caso de olvidarse la contraseña es posible recuperarla, indicando el email asociado se enviará un email a esa casilla.
- Snackbar para mostrar errores/cuando se ingresa correctamente

<img src="img/mobile/forgot_password.jpg" style="width:300px;" />

---

## Home

---

- Es la pantalla principal de la aplicación, se muestran albunes, canciones y playlists recomendadas basadas en la locación y géneros elegidos al registrarse.
- Hay también un botón que lleva a la pantalla de notificaciones.
- Se puede observar la nav bar inferior para navegar a otras pantallas

<img src="img/mobile/home.jpg" style="width:300px;" />

---

## Buscador

---

- Un buscador de canciones y artistas, posee cuatro formas de buscar, ya sea por el nombre de la cancion, el nombre del artista, el género o el tipo de suscripción.

<img src="img/mobile/search_name_vacio.jpg" style="width:300px;" />
<img src="img/mobile/search_name_lleno.jpg" style="width:300px;" />
<img src="img/mobile/search_artist.jpg" style="width:300px;" />

<img src="img/mobile/search_genre.jpg" style="width:300px;" />
<img src="img/mobile/search_subscription.jpg" style="width:300px;" />

- Al deslizar una canción esta se agrega a la queue, y al deslizar un artista se va a su perfil

<img src="img/mobile/add_to_queue.jpg" style="width:300px;" />
<img src="img/mobile/search_go_to_artist.jpg" style="width:300px;" />

---

## Reproductor

---

- Pantalla en la que pueden reproducirse canciones
- Se puede pausar, adelantar, atrasar, dar play, ir a la proxima cancion, ir a la anterior y acceder a la cola de canciones

<img src="img/mobile/reproductor.jpg" style="width:300px;" />

---

## Cola de canciones

---

- Se pueden observar las proximas canciones a reproducir

<img src="img/mobile/queue.jpg" style="width:300px;" />

---

## Library

---

- En esta pantalla se pueden ver los albunes, canciones y playlist del usuario.
- Se pueden agregar nuevas canciones, albunes y playlist dando click al boton correspondiente.
- Al hacer click en un album o playlist lleva a la pantalla del mismo.
- Al hacer click en una cancion se reproduce

<img src="img/mobile/library.jpg" style="width:300px;" />

---

## Album

---

- En esta pantalla se puede ver el contenido de un album

<img src="img/mobile/album_screen.jpg" style="width:300px;" />

---

## Playlist

---

- En esta pantalla se puede ver el contenido de una playlist

<img src="img/mobile/playlist_screen.jpg" style="width:300px;" />

---

## Creación de album

---

- Aqui se crea un nuevo album
- Se deben proporcionar datos como, nombre, descripcion, generos, tipo de suscription y una imagen.

<img src="img/mobile/create_album.jpg" style="width:300px;" />

---

## Creación de canción

---

- Aqui se crea una nueva canción
- Se deben proporcionar datos como, nombre, generos, tipo de suscription, album, el propio archivo de la cancion y los colaboradores que se deseen añadir.

<img src="img/mobile/create_song.jpg" style="width:300px;" />

---

## Creación de playlist

---

- Aqui se crea una nueva playlist
- Se deben proporcionar datos como, nombre, descripcion, lista de canciones y de colaboradores.

<img src="img/mobile/create_playlist.jpg" style="width:300px;" />

---

## Perfil del usuario

---

- En esta pantalla se puede observar el perfil del usuario
- Hay una lista de los albums y playlists que posee, y al hacerles click se pueden editar
- Hay un boton para acceder a la billetera del usuario, otro para ver su suscripción, otro para editar el perfil y por ultimo un boton para desloguearse

<img src="img/mobile/your_profile.jpg" style="width:300px;" />

---

## Editar album

---

- Al hacerle click a un album en el perfil se puede acceder a la pantalla para editarlo

<img src="img/mobile/edit_album.jpg" style="width:300px;" />

---

## Editar playlist

---

- Al hacerle click a una playlist en el perfil se puede acceder a la pantalla para editarla

<img src="img/mobile/edit_playlist.jpg" style="width:300px;" />

---

## Billetera

---

- Al hacerle click al boton de la billetera en el perfil se accede a la información de esta
- Se puede ver el balance y la dirección, la cual puede ser copiada

<img src="img/mobile/wallet.jpg" style="width:300px;" />

---

## Suscripción

---

- Al hacerle click al boton de suscripcion en el perfil se accede a la información de este
- Se puede ver el tipo de suscripcion actual y elegir un nuevo tipo de suscripcion

<img src="img/mobile/subscription.jpg" style="width:300px;" />

---

## Editar perfil

---

- Al hacerle click al boton de editar perfil, se puede cambiar el nombre y eliminar albunes, canciones y playlists.

<img src="img/mobile/edit_profile.jpg" style="width:300px;" />

---

## Perfil del artista

---

- Al deslizar un artista en el buscador se puede acceder al perfil de este
- Aqui se verán sus albunes y playlists, y hay un boton para enviarle un mensaje

<img src="img/mobile/artist_profile.jpg" style="width:300px;" />

---

## Lista de chats

---

- En esta pantalla se tiene un buscador de chats

<img src="img/mobile/chat_list.jpg" style="width:300px;" />

---

## Chat

---

- Luego de elegir un usuario con el que hablar, se puede ver la pantalla del chat

<img src="img/mobile/chat.jpg" style="width:300px;" />

---

## Notificaciones

---

- Al recibir un mensaje o ser añadido como colaborador a una playlist llegará una notificación a la app

<img src="img/mobile/notification.jpg" style="width:300px;" />
<img src="img/mobile/push_notification.jpg" style="width:300px;" />
