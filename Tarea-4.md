# Documentacion para 2 eval 

# Virtual Hosts

Empezaremos creando una carpeta con su index en el directorio " /var/www" Crearemos una para cliente y otra para servidor.

![Imagen del apartado](img/Tarea-4/1.PNG)

Dentro del index Pondremos algo para que se pueda visualizar al finalizar todo. Bastara con escribir dentro para poder comprobar que esta bien al escribir la direccion en el navegador.

![Imagen de la copia del fichero a cliente](img/Tarea-4/2.PNG)


![Imagen de la copia del fichero a servidor](img/Tarea-4/5.PNG)

Repetimos esto tanto con cliente y servidor, asi tendremos una base del fichero. Basicamente estamos copiando el fichero y al mismo tiempo asignando el nombre del nuevo fichero.

Para poder editarlo iremos al directorio y usaremos el comando "<b>nano</b>" para poder editar el fichero nuevo.

![Imagen del fichero cliente](img/Tarea-4/3.PNG)

Como se ve tendremos que escribir el DocumentRoot y el ServerName, tambien le daremos permisos. Repetiremos esto con los dos

![Imagen del fichero servidor](img/Tarea-4/4.PNG)

Ahora tenemos creados los archivos VirtualHost, ya solo queda habilitarlos para ello usaremos el comando "a2ensite".

Antes de eso tambien tendremos que deshabilitar el que viene por defecto.

![a2dissite del default](img/Tarea-4/9.PNG)

![a2ensite cliente](img/Tarea-4/7.PNG)

![a2ensite servidor](img/Tarea-4/8.PNG)

Despues de habilitarlo tendremos que reiniciar apache, para ello usaremos el comando que nos indica


![Reinicio de apache](img/Tarea-4/6.PNG)

Una vez hecho esto ya abremos finalizado, ahora comprobaremos si esta bien todo, para ello iremos al navegador y escribiremos la direccion.

![Comprobacion](img/Tarea-4/10.PNG)