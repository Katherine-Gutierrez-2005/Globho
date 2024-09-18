# Robot Aplicativo Web Globho 1.0 - 4.1 08/08/2024 - 16/09/2024

![image](https://github.com/user-attachments/assets/e467821a-ec78-4a4a-8202-feceaf7bedfc)

![image](https://github.com/user-attachments/assets/66a97c48-1b9a-4c54-947e-965be26939ab)


Aquí en este repositorio podemos encontrar diferentes versiones de un robot, pero que conforme aumenta el numero de su versión, más aumenta su capacidad dinámica para hacer muchas más tareas que una persona demora realizarlas en mucho tiempo

Primero que todo se le declaran variables y parámetros para darle indicaciones al robot que agarre los valores por defecto que va a tener cada uno, y así evitar manipular el script al momento de ejecutarlo en equipos diferentes.

Este robot lo que hace es: 

primeramente verifica si hay ventanas del Explorador de archivos abiertas, 

si las hay las cierra imediatamente(mediante la ayuda de un archivo python), 

si no las hay continúa con lo siguiente: ingresa a la URL especificada, 

ingresa unas credenciales de un usuario, va al apartado de reportes, 

va al apartado asistencial, selecciona un reporte, 

le indica la fecha en la cual se desea obtener el reporte, 

antes de descargarlo, averigua si hay mas reportes con el mismo nombre en comun y los elimina(mediante la ayuda de un archivo python), 

comienza a descargar hasta encontrar un reporte en especifico, 

lo selecciona y envía ese archivo a la carpeta principal donde está todo el programa, 

a la carpeta donde está el archivo (con extensión .pix) y los diferentes archivos (con extensión python .py) con los cuales el robot se comunica para ejecutar tareas complejas pero muy importantes para poder completar el propósito del robot en general.

luego le cambia el nombre mediante una concatenación  de variables/cadenas de el nombre por defecto que este trae mas la fecha actual, 

por ejemplo: "InfHistoriaPlano_2024-09-03", 

luego mediante un archivo python, 

se le indica al robot que dependiendo el mes en curso mande el archivo a esa carpeta, 

si no esta la carpeta del año y mes, 

las crea automáticamente y mueve el archivo hasta esta dirección, 

ya predeterminada en el archivo, 

por ultimo cierra ventanas de VS Code, Explorador de archivos, Navegador Google y PIX Studio.

Duración del Robot:1-2 minutos aproximados.
