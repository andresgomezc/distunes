# Distunes

Bienvenido al repositorio online de la web (inacabada) de Distunes: un proyecto de clase que incorpora *media queries* para el tema responsive y usa *node*, *gulp* y *sass* (entre más cosas).

Este proyecto fue desarrollado durante el segundo curso del *Grado en Diseño y Tecnologías Creativas* de la UPV.

### Instalaciones previas

Para la correcta ejecución de esta página web necesitarás tener instalado (por orden, ya que unos necesitan a otros):

1. Visual Studio Code (disponible [aquí](https://code.visualstudio.com/ "VSCode"))
2. NodeJs (disponible [aquí](https://nodejs.org/es/ "NodeJs"))
3. Nodemon (ejecutar el comando `npm install -g nodemon` en la terminal del sistema)
4. Gulp (ejecutar el comando `npm install -g gulp-cli` en la terminal del sistema)
5. Git (disponible [aquí](https://git-scm.com/downloads "Git")) (¿opcional?)

### Pasos a seguir una vez descargado/clonado

1. Abrir el proyecto con Visual Studio Code (arrastrando la carpeta del proyecto sobre el icono en el escritorio es suficiente).

2. Abrir la terminal interna (Menú > Ver > Terminal integrada)

3. Ejecutar el comando `npm install`. De esta forma se descargarán todas las dependencias que no se han subido para ahorrar espacio. Tarda unos minutos.

4. Ejecutar el comando `gulp img`. Este comando deberá ejecutarse siempre que añadamos una imagen al proyecto, para que pueda generarse en la carpeta "dist".

5. Ejecutar el comando `gulp`. Esto abrirá el navegador con *BrowserSync* para ver los cambios realizados en tiempo real.
