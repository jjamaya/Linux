# Linux
#Comandos Linux

1. Espacio libre en disco df -h /home/  ó  df -h /
2. Espacio usado du -hs /*  ó  du -hs .(directorio actual) du -hs *
3. Crear enlaces (accesos directos); ln -s ruta nombre_enlace 
4. Cambiar contraseña: passwd usuario
5. Añadir linea a archivo por comando:  echo nueva linea >> archivo.txt
6. Asignar permisos: chmod +r nombre_archivo
7. Buscar archivos o carpetas:  find . -name '*.mp3' / find . -name '*doc*' -type d  /  find . -name '*doc*' -type f  /  find . -size +2M  /   find -user javier      
8. curl a url: curl --location --request GET 'http://172.17.200.68:9005/'    curl --location --request GET 'localhost:8080/'
9. Saber las conexiones de red:  nmcli con

# Administración de software

1. Actualizar pauqetes:   apt-get update
2.Instalar aplicacion:  apt-get install vlc
3. Terminar de desinstalar rastros de softwaee:  apt-get purge vlc

# Redes

1. Conocer las redes de la maquina: nmcli con
2. Conocer la ip: /etc/hosts

### curl

CURL: Verifica conectividad.

curl --location --request GET https://www.redbus.co/  

curl --location --request POS T 'https://payments.bolivariano.com.co/EBOL_PROD/addi/check' \
--header 'Content-Type: application/json' \
--data-raw '{"amount":77000}'  

### Wget

WGET: Descarga rapida de archivos.

wget  https://www.redbus.co/
