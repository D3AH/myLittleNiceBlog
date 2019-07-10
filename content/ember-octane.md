---
title: Ember Octane
image:
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

Aquí una lista de blogs de introducción a octane:
+ [Native classes](https://www.pzuraq.com/coming-soon-in-ember-octane-part-1-native-classes/)
+ [Angle Brackets and named arguments](https://www.pzuraq.com/coming-soon-in-ember-octane-part-2-angle-brackets-and-named-arguments/)
+ [Tracked properties](https://www.pzuraq.com/coming-soon-in-ember-octane-part-3-tracked-properties/)
+ [Modifiers](https://www.pzuraq.com/coming-soon-in-ember-octane-part-4-modifiers/)
+ [Glimmer Components](https://www.pzuraq.com/coming-soon-in-ember-octane-part-5-glimmer-components/)

También hay otros interesantes sobre octane y parece que seguira publicando más.

### Documentación

A todo esto octane aun no se ha publicado oficialmente, es decir que es una `canary` version.
Esto significa que aun **falta terminar** algunas cosas y entre ellas está la **documentación**.

+ [Documentación en github](https://github.com/ember-learn/guides-source/tree/octane) (Recomendado)
+ [Documentación web](https://deploy-preview-455--ember-guides.netlify.com/release/)

Recomiendo revisar la documentación desde github, ahí es más sencillo estar atento si la sección ya fue actualizado o si siguen en proceso, etc.

### Optional features

Algo nuevo en ember, en cualquier edición, es [optional-features](https://guides.emberjs.com/release/configuring-ember/optional-features/).
Lo más destacado es que `jquery` ya no está incluido en ember por defecto, es ahora algo opcional:
```javascript
{
  "jquery-integration": true
}
```
Ejecutar `ember feature:list` no mostrara todas las opciones.