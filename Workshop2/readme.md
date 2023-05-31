# Workshop 02
##   Que necesitamos para desplegar una aplicación web?
- Servidor
- Dominio
- IP
- Una app (backend, frontend, fullstack)
- Una base de datos
- Presupuesto
- Seguridad
- Firewall

- SEO
 - Analítica


## Implementación  de servidor LAMP
### Cambiar nombre de host 
Para cambiar el nombre del equipo ejecutamos el siguiente comando.
sudo hostnamectl set-hostname webserver
sudo hostname para confirmar el nombre
exit
otra vez el ssh
## luego actualizamos la referencias de host del nombre de la maquina
cpn el comando sudo nano /etc/hosts
ahi cambiamos el nombre luego control o y luego control x


## Actualizar la lista de paquetes elegibles
sudo apt-get update // no instala nada solo  descarga la list de paquetes disponibles, como el menu del restaurante

## Instalamos la lista de paquetes
sudo apt-get install vim vim-nox \
    curl git apache2 mariadb-server mariadb-client \
    php7.4 php7.4-bcmath php7.4-curl php7.4-json \
    php7.4-mbstring php7.4-mysql php7.4-xml

