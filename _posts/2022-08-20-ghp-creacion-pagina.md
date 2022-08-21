---
layout: single
title: Creación de sitio web con Github Pages
excerpt: "GitHub Pages es una herramienta para poder publicar contenido alojado en un repositorio de GitHub. Esto permite que los usuarios puedan ver el contenido de su sitio web en una página web independiente."
date: 2022-08-20
classes: wide
header:
  teaser: /assets/images/htb-writeup-delivery/delivery_logo.png
  teaser_home_page: true
  icon: /assets/images/hackthebox.webp
categories:
  - Desarrollo web
tags:  
  - Páginas web
  - GitHub Pages
  - Markdown
---

![](/assets/images/htb-writeup-delivery/delivery_logo.png)

GitHub Pages es una herramienta para poder publicar contenido alojado en un repositorio de GitHub. Esto permite que los usuarios puedan ver el contenido de su sitio web en una página web independiente.

## ¿Cómo funciona?

Github Pages permite crear una página web independiente para cada repositorio de GitHub.
Para ello necesitamos un repositorio de GitHub y una cuenta de GitHub.


## ¿Cómo crear un repositorio de GitHub?

Para crear un repositorio de GitHub necesitamos una cuenta de GitHub. En la página de inicio de GitHub podemos crear un repositorio de GitHub, seleccionar el tipo de repositorio que queremos crear, público o privado, y pulsar el botón de crear.

![](https://https://github.com/MiguelCarrera8/web-site/assets/images/ghp-creacion-pagina/new-repo.png){width='100px'}

## ¿Cómo hacer una página web independiente?

Después de crear un repositorio de Github solamente tendríamos que irnos a los ajustes de ese repositorio y pulsar el botón de Pages.
Te mostrará dos opciones:
* Deploy from a branch
* Github actions

A día de hoy solamente he usado la opción de Deploy from a branch. En la página de configuración de Github Pages podemos elegir la rama que queremos publicar y el nombre de la página web que queremos crear, así como el tema que queremos usar. Después de esto tendremos una web para poder lanzar nuestro repositorio de Github.

![](https://https://github.com/MiguelCarrera8/web-site/assets/images/ghp-creacion-pagina/github-pages.png){width='100px'}


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