Digital Ocean 
================

## Recomandaciones
* Tener cuenta en gmail ( de preferencia )
* Tarjeta de credito/debito ( $5 minimo ) 
* OS: Windows/Linux/Mac


Para empezar a trabajar con Digital Ocean, vamos a realizar los siguientes pasos: 

1. Hacemos clic en este [Link](https://m.do.co/c/35f14306ae1c "Digital Ocean")

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do.png "Digital Ocean")

2. Ahora, en esta opcion, de preferencia, vamos a escoger **gmail** 

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do1.png "Digital Ocean")

3. Continuamos con el proceso de registro :) 

4. Nos logeamos en la plataforma.

Creacion de Droplet
========================

1. Dentro la plataforma vamos a escoger esta opción:

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do2.png "Digital Ocean")

2. Luego de hacer clic, escogeremos la opcion **droplet**

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do3.png "Digital Ocean")

3. Ahora, escogemos como sistema operativo: Centos, version:8.1

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do4.png "Digital Ocean")

4. Plan Standard

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do5.png "Digital Ocean")

5. Y ya para terminar, escogemos el tipo de instancia que deseemos, recordemos que, a mas infraestructura, mayor es el costo, pero mejor es la performance ;).

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do6.png "Digital Ocean")

### OBS.

No vamos a trabajar con datos/volumenes independientes, esta opcion la dejamos tal cual

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do7.png "Digital Ocean")

6. La regiion la dejaremos por defecto, recordemos, que, a las alejado el datacenter de sudamerica, la latencia aumenta ;) 

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do8.png "Digital Ocean")

7. En la parte de acceso a nuestro droplet, vamos a tener 2 opciones, la primera es crear un juego de llaves SSH ( opcion recomendable ), y la segunda es que nos envie el password a nuestro correo, para fines practicos, vamos a escoger esta opcion.

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do9.png "Digital Ocean")

8. Y finalizamos asignando un nombre para nuestro hostname de nuestro droplet.

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do10.png "Digital Ocean")

### OBS.
1. En esta opcion, podemos crear máximo 25 droplets en simultáneo.

2. Terminamos el proceso con : **Create Droplet**, el tema de backups tiene un costo, lo dejaremos como indica la pantalla sgt.

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do11.png "Digital Ocean")

3. Veremos esa pantalla, la cual nos muestra el proceso de creación de nuestro droplet.

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do12.png "Digital Ocean")


Conectandonos a nuestro Droplet
=================================

1. Vamos a ver esta pantalla, luego de terminar el proceso de instalacion del droplet:

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do13.png "Digital Ocean")

2. Como podemos visualizar, ya contamos con una **ip publica**, con la cual vamos a conectarnos a ella usando:

En Windows: 
* Cualquier cliente SSH, como por ejm: putty, xshell, bash from windows, etc.

En Linux/Mac:
* Abrimos la consola y realizamos el proceso de coneccion via SSH.

### OBS.
La constraseña de acceso es la que nos envciaron por correo ojo !!!! 

3. En esta parte, debemos colocar **2 veces** la contraseña que tenemos en nuestro correo

![DigitalOCean](https://github.com/kdetony/clouds/blob/master/images/do14.png "Digital Ocean")


Linode 
===========

## Recomandaciones
* Tener cuenta en gmail ( de preferencia )
* Tarjeta de credito/debito ( $5 minimo ) 
* OS: Windows/Linux/Mac

Para empezar a trabajar con Linode, vamos a realizar los siguientes pasos: 

1. Hacemos clic en este [Linode](https://www.linode.com/?r=c3f67a0321c98ae2eaa83be7238d678896b6b990 "Linode")

![Linode](https://github.com/kdetony/clouds/blob/master/images/linde.png "Linode")

2. Ahora, en esta opcion, completamos nuestro datos para nuestra cuenta

![Linode](https://github.com/kdetony/clouds/blob/master/images/linode1.png "Linode")

3. Luego, nos pedira confirmar nuestro correo para continuar con la instalacion

![Linode](https://github.com/kdetony/clouds/blob/master/images/linode2.png "Linode")

4. En nuestro correo electronico de registro, veremos este mensaje, al cual damos **confirm**

![Linode](https://github.com/kdetony/clouds/blob/master/images/linode3.png "Linode")

5. Ahora, en Linode, vamos a completar el registro :)


Creacion de Instancia Linode
============================== 

1. Nos ubicamos en esta seccion:

![Linode](https://github.com/kdetony/clouds/blob/master/images/linode4.png "Linode")

2. Escogemos la opcion linode

![Linode](https://github.com/kdetony/clouds/blob/master/images/linode5.png "Linode")

3. Ahora escogemos: OS: Centos, Version: 8.1, Location: Dallas

![Linode](https://github.com/kdetony/clouds/blob/master/images/linode6.png "Linode")

4. Aqui, vamoa a escoger las caracteristicas fisicas para nuestra instancia:

![Linode](https://github.com/kdetony/clouds/blob/master/images/linode7.png "Linode")

5. Y ya para finalizar, vamos a complear los datos para nuestra instancia: hostname

![Linode](https://github.com/kdetony/clouds/blob/master/images/linode8.png "Linode")

### OBS.
Tenemos la opcion tambien de generar llaves SSH para que sean asignadas a nuestra instancia ojo ! 

6. Hacemos clic en **CREATE**

![Linode](https://github.com/kdetony/clouds/blob/master/images/linode9.png "Linode")

Tambien les recomiendo SSDNodes:

[Link](https://www.ssdnodes.com/manage/aff.php?aff=1075 "SSDnode") 
