##Tarea 2 

El primer paso es crear una ip flexible. lo que hara esta ip flexible sera unir una ip "fija" a nuestro servidor así que aun que nuestro servidor cambie de ip todos los dias la ruta seguira siendo la misma.

Elegimos la opcion de Elastic IP
![putty ssh pam](imagenes/elastic-ip1.png)

Elegiremos la opcion de crear nunesra primera ipFleaxible 
![ip-flexible](imagenes/elastic-ip2.png)


![ipfelxible2](imagenes/elastic-ip3.png)

Despues de crearla tendremos que enlazarla con nuestro srvidor.
![enlazado](imagenes/elastic-ip4.png)

Elegimos la instancia y despues su ip
![instancia](imagenes/elastic-ip5.png)

En esta captura comprobaremos que nuestro servidor y nuestra ip felxible estan sincronizados correctamente.
![prueba-de-conexion](imagenes/elastic-ip6.png)