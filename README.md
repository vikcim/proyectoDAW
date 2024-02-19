# SISTEMAS DE CONTROL DE VERSIONES

## 'Vicent Gramage Doria" 
## `GitHub Pages https://github.com/vikcim/proyectoDAW.git`


`¿Qué es git?`

Git es un sistema distribuido de control de versiones, gratuito y de código abierto bajo licencia GPLv2. Fue diseñado originalmente por Linus Torvalds, el creador de Linux.

Gracias a Git, los desarrolladores tienen una gran facilidad para compartir su código, guardar los avances de sus proyectos, poder volver a atrás guardando un “histórico”, además de permitir el uso de ramas y las metodologías que nos permite y vamos a usar en este proyecto.


`¿Qué es una metodología en GIT y cual vamos a utilizar?`

En Git la denominación “metodología” se refiere a la estrategia de trabajo para un proyecto, la forma de ramificar el proyecto en qué puntos reunificar las ramas bifurcadas con “git merge nombreDeLaRama”.


La utilizada en este proyecto será la metodología con “Git Flow” con alguna pequeña variación, en la cual sobre la rama Master no se desarrolla código, solamente se hacen “merges” en momentos definitivos del proyecto, donde se le etiqueta una versión. En la rama que trabajamos a lo lago de la aplicación es la rama “developer” que es de la cual se hacen las ramas para los pequeños servicios y en la cual se hacen merge.


La mayor diferencia de “Git Flow” con nuestra metodología utilizada es que, dada la promiscuidad de realizar el proyecto por parte del equipo y su baja experiencia, las ramas en las que se realizaban los pequeños servicios erróneamente no han iniciado con la ruta “feature/” generando así un poco de desconcierto al observar las ramas actuales y poder diferencias las ramas principales de estas “subramas” de una forma rápida y eficaz.


## `PRACTICA EN GIT`

### `1 - Iniciando el repositorio y creando ramas. Usuario 1`

#### 1.- El usuario 1 crea el repositorio:

<img src="./usuario1/img/repositorio.png"  with="500" height="auto">

#### Repositorio de github:

```
https://github.com/vikcim/proyectoDAW.git
```

Clonado de repositorio

<img src="./usuario1/img/clonadorepo1.png"  with="500" height="auto">

Ramas develop y gh-pages

<img src="./usuario1/img/ramas1.png"  with="500" height="auto">

