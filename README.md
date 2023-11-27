# Apache
docker-compose
    -server apache : imagen,puertos,red e ip fija,volumenes
    -server dns: ""
    -cliente ubuntu

archivos conf DNS : default-zones, conf.local, conf.options
    -definimos ambos dominios  en conf.local y creamos sus db correspondientes en zonas

archivos conf Apache: httpd.conf, mime.types

archivos paginas Apache: paginas: con dos carpetas para las dos zonas


