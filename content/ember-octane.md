---
title: Ember Octane
image: /images/ember-octane_croped.png
imageMeta:
  attribution:
  attributionLink:
featured: true
authors: 
  - diegoauyon
date: Tue Jul 09 2019 01:55:57 GMT-0600 (Central Standard Time)
tags:
  - new
---

# Ember Octane

Qué es Octane, ember 4.0?

<iframe width="560" height="315" src="https://www.youtube.com/embed/hw07r_fwSSg?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

[Descripción rápida de que son "editions" y octane.](https://slides.com/michalstaskiewicz-1/ember-octane#/)

Aquí una lista de blogs de introducción a octane:
+ [Native classes](https://www.pzuraq.com/coming-soon-in-ember-octane-part-1-native-classes/)
+ [Angle Brackets and named arguments](https://www.pzuraq.com/coming-soon-in-ember-octane-part-2-angle-brackets-and-named-arguments/)
+ [Tracked properties](https://www.pzuraq.com/coming-soon-in-ember-octane-part-3-tracked-properties/)
+ [Modifiers](https://www.pzuraq.com/coming-soon-in-ember-octane-part-4-modifiers/)
+ [Glimmer Components](https://www.pzuraq.com/coming-soon-in-ember-octane-part-5-glimmer-components/)

También hay otros interesantes sobre octane y parece que seguira publicando más.

### Documentación

Octane aun no se ha publicado oficialmente, aun es `canary` version.
Por lo tanto aun **falta terminar** algunas cosas y entre ellas está la **documentación**.

+ [Documentación en github](https://github.com/ember-learn/guides-source/tree/octane) (Recomendado)
+ [Documentación web](https://deploy-preview-455--ember-guides.netlify.com/release/)

[Aquí](https://github.com/ember-learn/guides-source/blob/octane/guides/release/upgrading/editions.md) una guía de las nuevas funcionalidades.

Recomiendo revisar la documentación desde github, ahí es más sencillo estar atento si la sección ya fue actualizada o si siguen en proceso, etc.

### Optional features

Las versiones más recientes incluyen [optional-features](https://guides.emberjs.com/release/configuring-ember/optional-features/). Nos permite habilitar o deshabilitar ciertas funcionalidades de ember.
Por ejemplo: `jquery` ya no está incluido en ember por defecto. Para incluirlo:
```javascript
// config/optional-features.json
{
  "jquery-integration": true
}
```
Ejecutar `ember feature:list` muestra todas las opciones.

#### jquery
Algunas addons dependen de `jquery` por ejemplo `ember-ajax`. Por lo pronto parece que la meta es eliminar `jquery` como requerimiento. 
+ [Drop jquery requeriment](https://github.com/ember-learn/ember-simple-leaflet-maps/issues/2)

La alternativa de `ember-ajax` es [ember-fetch](https://github.com/ember-cli/ember-fetch).
