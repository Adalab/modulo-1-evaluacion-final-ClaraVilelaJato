![Adalab](https://beta.adalab.es/resources/images/adalab-logo-155x61-bg-white.png)

# Módulo 1 evaluación final Clara Vilela

Este es mi ejercicio de evaluación final para el primer módulo del curso de desarrollo web de Adalab, usando el Starter Kit que me han proporcionado en Adalab creado en **node y gulp**.

Los lenguajes que he utilizado para esta web son HTML5, CSS3 y el preprocesador SASS.

He trabajado en la carpeta `src/` y las carpetas `public/` y `docs/`, son generadas automáticamente cuando arrancamos el proyecto. El Kit lee los ficheros que hay dentro de `src/`, los procesa y los genera dentro de `public/` y `docs/`.

### Nota:

Necesitas tener instalado [Node JS](https://nodejs.org/)

Recuerda ejecutar los siguientes comandos si quieres trabajar en mi proyecto:

```bash
npm install

npm start
```

### Pasos para arrancar el proyecto:

Una vez hemos instalado las dependencias, vamos a arrancar el proyecto. **El proyecto hay que arrancarlo cada vez que te pongas a programar.** Para ello ejecuta el comando:

```bash
npm start
```

1. Y ya estaría!!!

Además, los comandos:

```bash
npm run push-docs
```

o

```bash
npm run deploy
```

son un atajo que nos genera la versión de producción y hace push de la carpeta `docs/` del tirón.

## Estructura de carpetas

La estructura de carpetas tiene esta pinta:

```
src
 ├─ api // los ficheros de esta carpeta se copian en public/api/
 |  └─ data.json
 ├─ images
 |  └─ logo.jpg
 ├─ js // los ficheros de esta carpeta se concatenan en el fichero main.js y este se guarda en public/main.js
 |  ├─ main.js
 |  └─ events.js
 ├─ scss
 |  ├─ components
 |  ├─ core
 |  ├─ layout
 |  └─ pages
 └─ html
    └─ partials
```

## Falta algo?

Echas de menos alguna mejora? Agradezco cualquier aportación a través de las issues o si te animas a mejorarlo mándame un PR :)
