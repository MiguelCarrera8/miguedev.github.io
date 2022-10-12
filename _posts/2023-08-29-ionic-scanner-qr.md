---
layout: single
title: Aplicación de Ionic Cordova para escanear códigos QR
excerpt: "Ionic es un Framework con el que podemos hacer aplicaciones híbridas con un solo código."
date: 2023-08-29
classes: wide
header:
  teaser_home_page: true
categories:
  - Desarrollo app
tags:  
  - Ionic
  -QR
  - Markdown
---

GitHub Pages es una herramienta para poder publicar contenido alojado en un repositorio de GitHub. Esto permite que los usuarios puedan ver el contenido de su sitio web en una página web independiente.

## ¿Cómo funciona?

Github Pages permite crear una página web independiente para cada repositorio de GitHub.
Para ello necesitamos un repositorio de GitHub y una cuenta de GitHub.


## ¿Cómo crear un repositorio de GitHub?

Para crear un repositorio de GitHub necesitamos una cuenta de GitHub. En la página de inicio de GitHub podemos crear un repositorio de GitHub, seleccionar el tipo de repositorio que queremos crear, público o privado, y pulsar el botón de crear.


<p align="center">
  <a href="#">
    <img alt="Github Pages" src="https://raw.githubusercontent.com/MiguelCarrera8/web-site/master/assets/images/ghp-creacion-pagina/new-repo.png"/>
  </a>
</p>


## ¿Cómo hacer una página web independiente?

Después de crear un repositorio de Github solamente tendríamos que irnos a los ajustes de ese repositorio y pulsar el botón de Pages.
Te mostrará dos opciones:
* Deploy from a branch
* Github actions

A día de hoy solamente he usado la opción de Deploy from a branch. En la página de configuración de Github Pages podemos elegir la rama que queremos publicar y el nombre de la página web que queremos crear, así como el tema que queremos usar. Después de esto tendremos una web para poder lanzar nuestro repositorio de Github.
<p align="center">
  <a href="#">
    <img alt="Github Pages" src="https://raw.githubusercontent.com/MiguelCarrera8/web-site/master/assets/images/ghp-creacion-pagina/github-pages.png"/>
  </a>
</p>


## ¿Cómo usar un tema para la página web?

En la página de configuración de Github Pages podemos elegir el tema que queremos usar.
El tema que he usado es el tema de minimal.

El repositorio del tema personalizado es el siguiente:

`https://github.com/slemire/slemire.github.io.git`

Para poder llevarlo a nuestro perfil de Github podemos realizar un *Fork* del repositorio.

En el archivo de `_config.yml` podemos cambiar todos los valores que queramos.

Estos son algunos de los valores que podemos cambiar.

```yml
locale: "es-ES"
title: "MiguelDev"
title_separator: "-"
name: "MigueDev"
description: "Mini proyectos de programación"
repository: "https://github.com/MiguelCarrera8/web-site.git"
```

Para poder crear o editar post debemos ir a la carpeta `_posts` y crear un archivo con el formato `YYYY-MM-DD-nombre-del-post.md`.

El lenguaje para crear un post es markdown, por lo que será sencillo crear un post con el formato que queramos.

Con esto podremos crear una página web independiente para dar a conocer nuestros proyectos, experiencias, etc.