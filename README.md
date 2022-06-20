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
