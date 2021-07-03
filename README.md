# Skeleton for UI React

Es un proyecto que implementa Skeletons como alternativa a los clasicos Loadings al momento de esperar la carga de la información como cuando se consume una API.

En este proyecto crearemos una pequeña aplicación que nos mostrará una lista de videos recomendados de Youtube.

## Instalación

Usaremos npm para instalar las dependencias que se encuentran en nuestro archivo `package.json`.

```bash
npm install
```

## Iniciar el proyecto

```bash
npm start
```

El comando `npm start` arrancará el proyecto el cual correrá sobre el puerto `localhost:3000` y nos mostrará la aplicación.

## react-loading-skeleton

Para esté proyecto se realizó la implementación de la libreria [react-loading-skeleton](https://www.npmjs.com/package/react-loading-skeleton) la cual nos permitirá crear los Skeletons que necesitaremos en la aplicación.

Para instalar este paquete es muy sencillo, solo necesitamos usar el siguiente comando:

```bash
npm install react-loading-skeleton
```

Esto nos agregará nuestra dependencia la cual podremos ver en nuestro archivo de configuración `package.json` de la siguiente forma.

```js script

 "dependencies": {
   "react-loading-skeleton": "^2.2.0",
 }

```

Para importar un Skeleton en algun componenete de React es muy sencillo, lo unico que debemos hacer es importar `Skeleton` de la libreria de `react-loading-skeleton`.

```js script
import Skeleton from 'react-loading-skeleton';

<Skeleton />; // Simple, single-line loading skeleton
```
