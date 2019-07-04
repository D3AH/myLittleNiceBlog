---
title: Comenzando Con Ionic
image: /images/ionic-components.png
imageMeta:
  attribution:
  attributionLink:
featured: true
authors: 
  - diegoauyon
date: Wed Jul 03 2019 17:22:03 GMT-0600 (Central Standard Time)
tags:
  - new
---

# Ionic

Ionic es un framework de código abierto que te permite utilizar todas las tecnologías web, que presumiblemente ya conoces, para desarrollar aplicaciones multiplataforma y por supuesta que también puedes hacer aplicaciones progresivas.

Este stack de herramientas te ofrece desarrollar aplicaciones de alta calidad en poco tiempo para varias plataforma. También un publicación continua de tus aplicaciones tan rapido como tu desarrollo. 

## Listo para comenzar

Primero debemos instalar la cli ionic globalmente:
```bash
npm install -g ionic
```

Iniciar una app:
```bash
ionic start myApp tabs
```
Al utilizar este comando creamos un app con el nombre de `myApp` desde la plantilla `tabs`

![tabs](https://ionicframework.com/img/getting-started/starter-app-thumbnails-2.png)

Para ejecutar esta app local:
```bash
cd myApp
ionic serve
```

## Ionic AppFlow
Respecto a la integración continua rápida ionic nos ofrece **Ionic AppFlow** un servicio que compila a binarios nativos nuestra aplicación y la permite compartir fácilmente con otros personas.

Para comenzar solo debes ejecutar este comando:
```bash
ionic link
```

## IonicNative
Ionic ofrece una lista de intregaciones para construir aplicaciones.
Estos son plugins para agregar funcionalidades nativas (cordova) a las aplicaciones.

Existen dos versiones:
+ Community Edition: mantenidos por la comunidad.
+ Enterprise Edition: mantenidos por el equipo de Ionic.

## UI Components
Las aplicaciones de ionic en alto nivel se construyen con componentes. La lista de componentes es algo larga pero estos son algunos:
+ Action sheet
+ Icons
+ Cards
+ Floating action point
+ Input
+ Modal
+ Navigation

Muchos otro más.