# REDES2_2S2020_Practica1_201503750
## INSTANCIA EC2
-Nos vamos al apartado de instancias en la consola aws
-Le damos launch instance
-Seleccionamos Ubuntu Server
-Seleccionamos el tipo de hardware en este caso utilizamos t2.micro
-Creamos una vpc para configurar el trafico de nuestra ec2
-En el ultimo paso configuramos un Security group 
-Permitimos que solo tenga acceso http para evitar ataques SSH

## SERVIDOR HTTP (APACHE2)
-Actualizamos los paquetes (sudo apt-get update)
-Instalamos apache 2 (sudo apt-get install apache2)
-Luego de crear la pagina html, se debe copiar todos los recursos necesarios a la ruta
/var/www/html
