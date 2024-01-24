# Tarea Evaluable 2.1 Dockerización de stack LAMP

## Paso 1
### Descargamos y preparamos las carpetas necesarias con el contenido.
![Descargar Recursos](./img/capt1.png)

## Paso 2
### Creamos una imagen de Docker donde incluimos Apache y PHP 
![Descargar Recursos](./img/capt2.png)
![Descargar Recursos](./img/capt3.png)

## Paso 3
### Creamos el fichero docker compose.yml.
![Descargar Recursos](./img/capt4.png)
![Descargar Recursos](./img/capt5.png)
![Descargar Recursos](./img/capt6.png)

## Paso 4
### Definimos la network y lo enlazamos con www.
![Descargar Recursos](./img/capt7.png)
![Descargar Recursos](./img/capt8.png)

## Paso 5
### Definimos el servicio db para construir un contenedor en MySql.
![Descargar Recursos](./img/capt9.png)
![Descargar Recursos](./img/capt10.png)
![Descargar Recursos](./img/capt11.png)
![Descargar Recursos](./img/capt12.png)
![Descargar Recursos](./img/capt13.png)
#### Red tipo bridge: es un dispositivo de interconexión de redes que conecta segmentos de red de diferentes topologías y arquitecturas

#### Red tipo lamp-network: LAMP es el stack de tecnologías más usado en la actualidad, todas ellas de código abierto, con un porcentaje de penetración que supera de largo el 50% de los sitios web.

## Paso 6
### Realizamos cambios en la zona del contenedor PHPMyAdmin.
![Descargar Recursos](./img/capt14.png)

## Paso 7
### Definimos la precedencia de arranque de los contenedores, para que los servicios www y phpmyadmin deban esperar a que el servicio mysql esté en ejecución.

#### Levantamos el docker compose
![Gif](./img/gif1.gif)
