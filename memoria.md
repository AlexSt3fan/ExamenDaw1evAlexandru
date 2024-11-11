# Examen DAW 1ºEvaluación
>
## Indice:
* Introducción
* Motivación
* Conclusión
* Webgrafía
* Ejercicio 1
* Ejercicio 2
* Ejercicio 3
>
## Introducción
Este 11 de noviembre del 2024 a las 15:00 de la tarde tuve que presentarme al examen de DAW si no quisiera suspender.
>
## Motivación:
Examen de Daw 1ºEvaluación
>
## Conclusión:
Hoy se realizó el examen de la primera evaluación de Daw consistiendo de 4 preguntas (la última fue la redacción de esta memoria).
>
### Webgrafia:
1. https://www.hostinger.es/tutoriales/linux-comandos?authuser=0#1_Comando_ls
2. https://www.digitalocean.com/community/tutorials/how-to-use-ssh-to-connect-to-a-remote-server-es?authuser=0
>
## Ejercicio 1:
Consiste de un cuestionario tipo de test que puntua 3 puntos.
>
## Ejercicio 2:
Consiste en la conexión del servidor proporcionado por el procesor para crear un archivo .txt con nuestro nombre y apellidos en el Escritorio.
### Conexión al servidor:
Mediante el comando ssh nos conectaremos al servidor mediante el nombre de usuario y la ip.
![Captura desde 2024-11-11 17-40-51](https://github.com/user-attachments/assets/f0e6730c-ee24-4a48-b664-3b0600eb4860)
### Creación de archivo:
Nos iremos al directorio del Escritorio para crear AlexandruStefanGheorghe.txt, lo rellenaremos con el resultado de dos comandos *whoami* que muestra que usuario estamos utilizando y  el nombre del comando *who* que muestra a todos los usuarios que hay en el servidor.
![Captura desde 2024-11-11 17-47-34](https://github.com/user-attachments/assets/ac7f767f-0a40-4730-a3df-c836d5bfe4bd)
![Captura desde 2024-11-11 17-48-54](https://github.com/user-attachments/assets/0a1e88c4-53f9-4105-9b22-ceea3ea25f3f)
![Captura desde 2024-11-11 16-45-58](https://github.com/user-attachments/assets/8d33869b-0e6c-4d68-be9f-f3e0500bd48d)
>
## Ejercicio 3:
Consiste en la creación de un hostvirtual que muestre el contenido de index.html a traves de un dominio.
### Creación del directorio *miWeb*:
Para la creación del hostvirtual es necesario primero entrar dentro de la ruta /var/www/ y allí se creará *miWeb*.
![Captura desde 2024-11-11 18-01-42](https://github.com/user-attachments/assets/7d8be651-ce5c-4625-bc06-64833fda546d)
![Captura desde 2024-11-11 18-02-20](https://github.com/user-attachments/assets/9859c61e-3c48-4cff-99f3-db9cce36bb19)
Con el comando *ls* podemos ver si realmente está creado.
### Creación de *index.html*:
Crearemos dentro de /var/www/miWeb/ un archivo index.html que mostrará el contenido.
![Captura desde 2024-11-11 18-07-07](https://github.com/user-attachments/assets/3e68dd37-9e04-4945-a3c6-ab697f33498f)
![Captura desde 2024-11-11 18-09-02](https://github.com/user-attachments/assets/7a5e22f8-43e2-4815-9682-e6bd1802ac7e)
### Creación del dominio y su configuración:
Procederemos a crear el dominio *miweb.com* y su configuración *miweb.conf*, para ello debemos de ir al directorio de sites-avalible.
![Captura desde 2024-11-11 18-12-42](https://github.com/user-attachments/assets/801394ee-44e1-40e2-86ab-921177eefe40)
Acto seguido procedemos a crear miweb.com y miweb.conf en base al archivo 000-default.conf ya que no es una copia exacta, modificaremos el DocumentRoot y ServerAdmin, en Documentroot pondremos la dirección de miWeb y en cuanto a ServerAdmin valdrá con un correo electronico para recibir avisos.
![Captura desde 2024-11-11 18-14-17](https://github.com/user-attachments/assets/1435fe6b-779b-4d3d-91e9-8b4115ce6536)
![Captura desde 2024-11-11 18-21-26](https://github.com/user-attachments/assets/ddfa8fab-d3ad-433f-8bb7-bf7cf7dd2a63)
Una vez hecho eso tenemos que activar la configuración y reiniciar el sistema.
![imagen](https://github.com/user-attachments/assets/689e555b-95db-4901-a2c7-6e0863dd88bb)







