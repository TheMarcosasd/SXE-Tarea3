

La siguiente práctica es una lista de tareas que tenéis que hacer. 
Por cada tarea tenéis que ir poniendo los comandos utilizados y, brevemente, describir el proceso y como compruebas que se ha realizado lo pedido en un fichero (nombre "Readme.md") con formato markdown.
Crear un repositorio en github para subir este fichero
Cada dos apartados tenéis que hacer un commit nombrando el numero del apartado
En la respuesta pon el enlace a tu repositorio en github
Utiliza la imagen de Apache, tag 2.4 y apoyandote en la mini guía de docker sigue las instrucciones: <br>

   1 Descarga la imagen 'httpd' y comprueba que está en tu equipo. <br>
   2 Crea un contenedor con el nombre 'dam_web1'. <br>
   3 Si quieres poder acceder desde el navegador de tu equipo, ¿que debes hacer? <br>
   4 Utiliza bind mount para que el directorio del apache2 'htdocs' esté montado un directorio que tu elijas. <br>
   5 Realiza un 'hola mundo' en html y comprueba que accedes desde el navegador. <br>
   6 Crea otro contenedor 'dam_web2' con el mismo bind mount y a otro puerto, por ejemplo 9080. <br>
   7 Comprueba que los dos servidores 'sirven' la misma página, es decir, cuando consultamos en el navegador: <br>
       http://localhost:9080  <br>
       http://localhost:8000  <br>
   8 Realiza modificaciones de la página y comprueba que los dos servidores 'sirven' la misma página
   
Lo primero seria descargar la imagen, para descargarla visitamos docker hub y buscamos httpd.
   
![Screenshot_20241021_143504](https://github.com/user-attachments/assets/a1b143a0-5c85-4009-b573-1e68eae2f795)

Confirmamos que se haya descargado.
   
![Screenshot_20241021_143529](https://github.com/user-attachments/assets/d6525e4f-5aa3-4d1e-9ab0-009791bd036c)

Creamos un contenedor y le damos imagen. Ademas confirmamos que se haya creado.

![Screenshot_20241021_143852](https://github.com/user-attachments/assets/60f45bf6-1476-414d-be26-c65c07d8f9ab)

   
