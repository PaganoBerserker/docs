---
title: Git & Gitflow Cheetsheet  ES
author: Decentralized Climate Foundation
date: 2023-03-15
category: git-flow
layout: post
---

## GIT 

---

### Comandos de Git basicos o frecuentes


```shell

$ git init # Crear un nuevo git
 
$ git add # Agregar archivos al area de preparacion
 
$ git status # Estado del repositorio
 
$ git  commit -m # pasar archivos del area de preparacion al repositorio local
 
$ git log # ver las versiones de archivos del repositorio
 
$ git clone # clonar un repositorio remoto
 
$ git push # modificar el repositorio remoto, con su nueva actualizacion
 
$ git pull # actualizar tu repositorio local con la ultima version del remoto
 
$ git add . # sirve para agregar todos los archivos modificados al area de preparacion

```

---

## GIT FLOW 
---

### Instalar en linux debian
Para instalar git flow, se requiere tener previamente git, y se executan los siguientes comandos en tu terminal ya sea con sudo o como root.

```

$ sudo apt-get update

$ sudo apt-get install git-flow

```



### INICIALIZAR
Una vez que estas dentro de tu directorio git o repositorio clonado, inicializa el git flow:
```

$ git flow init

```

### RAMAS DE GIT FLOW

![](https://www.campingcoder.com/post/20180412-git-flow.png)

* **Master**: Rama principal que mantiene la version estable de un software.
* **Develop**: Rama que se utiliza por uno o varios programadores para un software en modo pruebas. 
* **Feature**: Rama temporal o local, que sirve para que cada programador desarrolle alguna funcion especifica (Libreria, funcion, clase, etc.). 
* **Release**: Rama temporal solo para publicar las etiquetas de versiones y sincronizar develop con master, esto se hace cuando tenemos una version estable de software o un punto para entregable.
* **Hotfix**: Rama temporal que se utiliza para arreglar errores criticos o bugs en el codigo de produccion, generalmente se utiliza en modo de emergencia.


#### FEATURES


---


**1. COMENZAR UNA CARACTERISTICA (FEATURE)**

```
$ git flow feature start MYFEATURE

```
> Cambiar `MYFEATURE` por el nombre que le quieras dar a tu característica.
---

**2. FINALIZAR UNA CARACTERISTICA**

```

$ git flow feature finish MYFEATURE # Finaliza el desarrollo de una cacteristica.

$OBTENIENDO CARACTERISTICAS PUBLICADAS

$ git flow feature pull origin MYFEATURE # Obten una caracteristica publicada por otro.

$ git flow feature track MYFEACTURE # Puedes mantener un seguimiento de tus cambios.


```

#### RELEASE
---

**COMO PUBLICAR UNA VERSION**

```
$ git checkout master
 
$ git pull
 
$ git checkout develop
 
$ git pull
 
$ git flow release start 1.0
 
$ git flow release publish 1.0
 
$ git flow release finish 1.0
 
$ git push origin --all --follow-tags

```

---

#### HOTFIX
---

**COMO PUBLICAR HACER UN HOTFIX**

```

$ git checkout develop
 
$ git pull
 
$ git checkout master
 
$ git pull
 
$ git flow hotfix start (Nombre)
 
# Hacer cambios
 
$ git status # verifique el archivo de color rojo
 
$ git add . # agregar archivos
 
$ git commit -m 'Escribe un comentario'
 
$ git flow hotfix finish (name)
 
# Recuerda poner una etiqueta de versión fija 1.2.x por ejemplo 1.2.2
# estabas en el maestro, y luego debes estar en la rama de desarrollo
 
$ git push origin --all --follow-tags

```

## LICENSE

```
Copyright (C) 2023 DECENTRALIZED CLIMATE FOUNDATION A.C.
Permission is granted to copy, distribute and/or modify this document
under the terms of the GNU Free Documentation License, Version 1.3
or any later version published by the Free Software Foundation;
with no Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.
A copy of the license is included in the section entitled "GNU
Free Documentation License". 
```

## CONTACTO Y DESARROLLADORES
> Work developed in collaboration with the [Decentralized Climate Foundation](https://decentralizedclimate.org).

- [Gustavo Bermudez](nizaries44@gmail.com)

Revisor:

- [David E. Perez Negron R.](mailto:david@neetsec.com)

---

## REFERENCIAS
\[1\]  Daniel Kummer, "Git-flow cheatsheet", https://danielkummer.github.io/git-flow-cheatsheet/index.html), 2023.

\[2\] www.campingcoder.com, "How to use git flow", https://www.campingcoder.com/2018/04/how-to-use-git-flow/, 2023.
