---
layout: single
title: Comandos basicos de linux
date: 2022-02-23
classes: wide
header:
  teaser: /assets/images/slae32.png
categories:
  - linux
tags:
  - parrot
  - comandos
  - linux
---

### Comandos basicos linux
-----------------------------
Hoy vamos a ver los comandos basicos de linux para asi entender un poco mas como funciona.

### Lista de comandos
----------------------
Aqui te dejare una serie de comandos para que los veas, mas abajo dejare una explicacion de para que sirven:

```
sudo su

sudo apt update

sudo parrot-upgrade

ls

cd

mkdir

touch

rm

rm -r
```

### Explicacion de comandos:
----------------------------

#### sudo su:

El comando sudo su sirve para entrar en modo root, es decir, administrador. Una vez lo ejecutemos nos pedira nuestra contraseña. Es importante aclarar que si no estas seguro de lo que estas haciendo no uses este modo, ya que facilmente podemos tirar todo lo que hicimos a la basura y tengamos que reinstalar nuestro sistema.


#### sudo apt update:

Este comando sirve para listar los paquetes que podemos actualizar.


#### sudo parrot-upgrade / sudo apt-get upgrade:

El comando sudo parrot-upgrade se utiliza en Parrot OS, en cambio sudo apt-get upgrade sirve la mayoria de los sistemas basados en linux. Su funcion es descargar y actualizar el sistema.


#### pwd:

El comando pwd se utiliza para ver la ruta donde estamos localizados.


#### ls:

El comando ls se utiliza para listar los archivos y carpetas de el directorio donde nos encontramos actualmente.


#### cd:
Este comando se utiliza para entrar a un directorio(Ejemplo: cd ~/Descargas). Podemos ayudarnos con el comando ls para saber que carpetas hay en nuestro directorio actual.


#### mkdir: 

Este comando es utilizado para crear carpetas. 
```
mkdir nombre-de-carpeta
```

#### touch:

El comando touch se utiliza para crear archivos. Deberemos agregarle una extension al final (.py,.txt,etc)
```
touch nombre-de-archivo.extension
```

#### rm y rm -r

Los comandos rm y rm -r se utilizan para eliminar archivos y carpetas, respectivamente.

```
rm archivo.txt

rm -r carpeta
```
-----------------------------------

Estos son los comandos mas basicos que hay que saber para familiarizarnos con el entorno. Mas adelante ire actualizando con comandos intermedios hasta comandos nivel expertos.
