# AlertaVioleta
Aplicacion Alerta Violeta para el IMM, Creada en IONIC con Angular y plugins de Cordova

Aviso:
Esta aplicacion esta desarrollada en Ionic para su facil implementacion tanto en Android como en iOS (Inclusive la puedes usar en la computadora solamente que acciones como mandar mensaje o realizar una llamada no funcionaran, pero tu codifo de verificacion sera mandado a la consola podras tener un vistazo), y esta construida para plataforma Android (Debidoa a que para construirla para iOS se necesita una Mac) por lo que puede ser utilizada de un inicio en android, en caso de hacer una modificacion al codigo o querer construirla para iOS es necesario volver a construir el proyecto, instalando el Cliente de Ionic, Cordova y los requerimientos para cada plataforma.

Instrucciones para su utilizacion:
  1. Descargar toda la carpeta.
  2. Tener instalado Android Studio.
  3. Abrir la carpeta en la ubicacion 'NombredelaCarpeta/platforms/android'.
  4. Conectar el dispositivo.
  5. Cargar la aplicacion al dispositivo.

Instrucciones para construir el proyecto:
  1. Tener abierto el pryecto en una ventana git.
  2. Tener instalado el Cli de Ionic.
  3. Tener Instalado Cordova.
  4. Tener los requerimientos de cada plataforma instalados.
  5. Ejecutar el comando 'ionic cordova platform add _Platform_' siendo _Platform_ la plataforma a ser utilizada (ios/android), en el caso de android previamente se incluyo.
  6. Ejecutar el comando 'ionic cordova build _Platform_' siendo _Platform_ la plataforma a ser utilizada (ios/android).
  7. Listo dentro de la carpeta de platforms se tendra el proyecto para compilar en el editor de cada plataforma (Android Studio/XCode).

Instrucciones ejecutar en la misma computadora:
  1. Tener abierto el pryecto en una ventana git.
  2. Tener instalado el Cli de Ionic.
  3. Tener Instalado Cordova.
  4. Ejecutar el comando 'ionic serve'.
  5. De esta manera tendras la aplicacion corriendo en tu localhost y podras utilizarla, los datos de verificacion se pueden ver en consola.

Recomendaciones extra:
  1. Tener instalado previamente el Cliente de Ionic para evitar problemas.
  2. En caso de querer ver errores como desarrollador utiliza Toasts para indicarlos una vez este en el dispositivo.
  3. La aplicacion en la primera utilizacion pedira muchos permisos, concederlos para no tener problemas posteriormente.
