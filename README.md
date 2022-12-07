Instalar NodeJs

1. Entrar en https://nodejs.org/es/download/ y descargar el instalador de Node.js en el sistema operativo deseado. Podemos elegir entre Windows, Mac y Linux.

![Image text](https://github.com/RivanPP/ProyectFinalV2.github.io/blob/main/nodejs1.png)

2. Ejecutar el instalador que acabamos de descargar. Simplemente debemos avanzar en el proceso de instalación.

![Image text](https://github.com/RivanPP/ProyectFinalV2.github.io/blob/main/nodejs2.png)

3. Una vez finalizado el proceso de instalación, podemos comprobar fácilmente si se nos ha instalado correctamente. Para ello, vamos al intérprete de comandos de nuestro ordenador (en Windows, por ejemplo, escribir “cmd” en la barra de búsqueda y abrir la aplicación de “Símbolo del sistema”).

![Image text](https://github.com/RivanPP/ProyectFinalV2.github.io/blob/main/nodejs3.png)
![Image text](https://github.com/RivanPP/ProyectFinalV2.github.io/blob/main/nodejs4.png)

4. En la ventana de comandos, escribir node -v y pulsar la tecla Enter. Nos debería aparecer la versión que tenemos instalada de Node.js (en mi caso la versión 12.19.0). Para comprobar que se nos ha instalado también NPM, escribiremos npm -v y pulsaremos de nuevo Enter. Nos debería aparecer también en este caso la versión del Node Package Manager (en mi caso la versión 6.14.8).
![Image text](https://github.com/RivanPP/ProyectFinalV2.github.io/blob/main/nodejs5.png)

Con estos 4 sencillos pasos ya tendremos instalado y disponible para utilizar todo el potencial de Node.js junto con el instalador de paquetes NPM.


Instalar React

Paso 1. Instalar NodeJS en su ultima versión, para eso entraremos a su web oficial y descargaremos el instalador más actualizado https://nodejs.org/es/


Paso 2. Actualizar NPM, el gestor de paquetes de node, para bajarnos las dependencias más actuales:


npm install -g npm@latest


Paso 3. Borrar la cache de NPM:

npm cache clean --force

Paso 4. Instalar Create React App, que es un interprete de consola(CLI) que nos va a permitir instalar React facilmente e incluirá webpack para la compilación y minificación del proyecto, un live reload, una estructura básica para los proyectos de ReactJS, etc, veamos como instalar este paquete:

npm install -g create-react-app

Ahora ya tenemos instalado «create react app» y ya podemos generar un nuevo proyecto de React.js

Para generar un nuevo proyecto de React.js y finalmente instalarlo, entraremos al directorio donde queramos generar el proyecto de reactjs y ejecutamos este comando:

create-react-app NombreDeMiProyecto

Ahora entraremos al directorio de nuestro proyecto y lanzaremos el servidor local de pruebas para React:

cd NombreDeMiProyecto
npm start

Puedes comprobar la versión de React que tienes dentro del fichero package.json.

Ahora tendremos disponible la webapp de React 16 en http://localhost:3000/ y veremos nuestro proyecto corriendo, con la página de bienvenida por defecto.

Con esto ya sabemos como instalar React desde cero y como generar un proyecto base.
