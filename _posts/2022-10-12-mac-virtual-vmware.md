---
layout: single
title: Virtualizar máquina de MacOS.
excerpt: "En VMWare podemos virtualizar un sistema operativo de Mac con varios pasos sencillos"
date: 2022-10-12
classes: wide
header:
  teaser_home_page: true
categories:
  - VMWare
tags:  
  - MacOS
  - VMWare
---

Para poder realizar este tutorial correctamente debemos tener instalada la versión de VMWare workstation 16 player

## ¿Cómo empezamos?

Para empezar debemos descargarnos el <a href="https://github.com/paolo-projects/auto-unlocker/releases/tag/v2.0.0a">Auto-Unlocker</a> , instalarlo correctamente y ya deberá aparecernos la opción de seleccionar el sistema operativo <strong>MacOS</strong>

<p align="center">
  <a href="#">
    <img alt="MacOS" src="https://raw.githubusercontent.com/MiguelCarrera8/web-site/master/assets/images/mac-virtual-vmware/opcion-macos.png"/>
  </a>
</p>

## ¿Qué necesitamos para poder crear la máquina virtual?

Para poder crear la máquina virtual necesitamos la iso de <a href="https://gofile.io/d/FK1m66">MacOS Monterrey</a>, tras la descarga solamente deberemos crear una máquina virtual como cualquier otra realizando los siguientes pasos :

  - Crear máquina virtual.
  - Instalar sistema más tarde.
  <p align="center">
  <a href="#">
    <img alt="Paso 2" src="https://raw.githubusercontent.com/MiguelCarrera8/web-site/master/assets/images/mac-virtual-vmware/pasos-maquina.png"/>
  </a>
  </p>

  - Seleccionar el sistema operativo Apple MacOS y el número de la versión
  <p align="center">
  <a href="#">
    <img alt="Paso 3" src="https://raw.githubusercontent.com/MiguelCarrera8/web-site/master/assets/images/mac-virtual-vmware/pasos-maquina-2.png"/>
  </a>
  </p>

  - Introducimos el nombre y la ubicación de nuestra máquina virtual.
  - Seleccionamos la memoria del disco y opcionalmente customizamos los componentes.
  
## Lanzamos la máquina virutal

Si todo ha salido bien solamente tendremos que lanzar la máquina virtual y saldrá el logo de Apple.

Seleccionaremos el idioma y después clicaremos en "Utilidades de disco", seleccionaremos el disco creado de la máquina virtual y lo borraremos :

<p align="center">
  <a href="#">
    <img alt="Paso 3" src="https://raw.githubusercontent.com/MiguelCarrera8/web-site/master/assets/images/mac-virtual-vmware/pasos-maquina-3.png"/>
  </a>
  </p>

## Nuevo disco para nuestro sistema

Deberemos poner los valores tal como se muestran en la imagen :

<p align="center">
  <a href="#">
    <img alt="Paso 3" src="https://raw.githubusercontent.com/MiguelCarrera8/web-site/master/assets/images/mac-virtual-vmware/pasos-maquina-4.png"/>
  </a>
  </p>

## Instalación del sistema

Cerraremos la ventana de utlidades de disco cuando se haya borrado el disco correctamente, seleccionaremos instalar Mac, seleccionaremos el disco y seguiremos los pasos correspondientes que nos indique el proceso de instalación del sistema operativo.

#### Si hemos seguido correctamente los pasos podremos tener un Mac virtualizado con todas sus funcionalidades disponibles.