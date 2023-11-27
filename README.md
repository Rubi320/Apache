# Instalacion de Apache+Virtual Host

### Primero debemos crear un docker compose:

 - server apache : imagen,puertos,red e ip fija,volumenes : 1 a configuracion de apache y otro a paginas web
 - server dns:          "  "
 - cliente ubuntu

### Necesitamos una carpeta para la configuracion del DNS

 - default-zones : zonas por defecto
 - conf.local : definimos aqui los dominios que queremos utilizar y sus bases d datos
 - conf.options : fowarders de google ..

### Creamos una carpeta para almacenar las zonas del DNS

*** Aqui definimos las bases de los dominios a utilizar simplemente es el mismo archivo pero cambiando el nombre de la zona ***

- ns A 'ip fija DNS'
- www A 'ip fija Apache'

    
### Necesitamos otra carpeta para la configuracion del APACHE

- httpd.conf : esta es la configuracion de nuestro server
- mime.types

### Creamos otra carpeta para almacenar las paginas

### Crear los virtual hosts

*** Debemos definirlos dentro del archivo httpd.conf indicando la raiz de cada servidor y su nombre. ***
