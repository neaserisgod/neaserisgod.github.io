---
layout: single
title: Instalar Parrot OS
date: 2022-02-23
classes: wide
header:
  teaser: /assets/images/slae32.png
categories:
  - linux
  - virtual machine
tags:
  - parrot
  - vmware
  - linux
---
Hoy vamos a ver como instalar Parrot OS en una maquina virtual,para asi poder dar nuestros primeros pasos con linux. 

### ¿Que es Parrot OS?
---------------
Antes de nada,debemos saber que es Parrot y para que sirve. Parrot OS es una distribución linux enfocada a pentesters. Como toda distribucion linux,
es muy personalizable,aparte de ser muy poco exigente si de recursos hablamos.

### Instalando Parrot OS
---------------
Para empezar,deberemos instalar [VMware](https://drive.google.com/drive/folders/1hD6xUQ-1xS_X6h7cpd6SFuYLAMSgk4cu?usp=sharing)
, que suele ser de pago pero aqui te deje un link para descargarlo completamente gratis. La contraseña es binajtec. 
 Luego descargaremos [Parrot OS](https://parrotsec.org/security-edition/). Elegimos la version MATE Desktop. 
 (Es importante descargar el archivo ISO para asi personalizarlo a gusto, si descargamos el archivo para maquina virtual no podremos hacer una instalacion completa). 
 A continuacion te dejare los pasos a seguir para llevar a cabo la instalacion.

Pasos a seguir:
1.  Descargamos Parrot OS y VMware.
2.  Instalamos VMware.
3.  Entramos a VMware y seleccionamos "Create a new virtual machine".
4.  Elegimos "Custom".
5.  Damos click en "Siguiente" hasta que nos aparezca "Install from" y seleccionamos "Installer disk image file (iso)" y seleccionamos la imagen de Parrot OS.
6.  Damos click en "Next", asignamos el nombre y donde queremos guardar nuestra maquina virtual.
7.  Asignamos 2 cores per processor, asignamos 4gb de ram y clickeamos en "Next" hasta llegar al final y damos click en "Finish.
8.  Se nos iniciara la maquina, damos Enter en "try/install". Una vez iniciado el sistema damos doble click en "install parrot os" o similar, 
 elegimos el idioma y seguimos todos los pasos (al seleccionar idioma del teclado,si eres de LATAM seleccionar como idioma "Español latinoamericano" y en teclado "default",
asi todos las teclas funcionaran como deben.
9.  Una vez terminado el proceso la maquina se reiniciara, si ciframos el disco tendremos que poner la contraseña del cifrado, 
 esperamos unos segundos y estaremos en la pantalla de inicio de sesión.

### Actualizar Parrot OS

Una vez dentro del sistema abrimos una terminal y ponemos los siguientes comandos:
```
sudo apt update
sudo parrot-upgrade
```
### Felicitaciones

Si has llegado hasta aqui significa que has seguido los pasos al pie de la letra y ya tienes tu entorno linux 100% funcional.
