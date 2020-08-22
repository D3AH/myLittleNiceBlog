---
title: "Production without monitoring, isn't production: Reporting errors"
image: /images/tags.jpg
imageMeta:
  attribution:
  attributionLink:
featured: true
authors:
  - diegoauyon
date: Tue Jun 12 2018 17:57:10 GMT+0100 (IST)
tags:
  - monitoring
---

"Production without monitoring, ins't production" en esta serie, voy a demostrar que herramientas utilizo para monitorear aplicaciones.
Trabajar con aplicaciones sin herramientas de monitoreo es una muy mala experiencia para el usuario y para el desarrollor.
Es muy importante la recolección de información, dar soporte a usuarios cambia cuando no tienes que interegorrarlos *win-win*.

Ok, en está seria abordare varios tipo de información que monitorear. Lo ordene según mi prioridades.

La serie consiste en las siguientes partes:
+ Monitoreo de errores
+ Monitoreo de logs
+ Monitoreo de rendimiento (APM) 

El monitoreo de errores es sencillo explicar, es prácticamente cuando occure una excepción en la aplicación.

> Para realizar la serie utilizare un aplicación de Django de ejemplo.

## Instalar Sentry
## Configurar Django
## Configurar Slack
## Configurar correo electrónico
