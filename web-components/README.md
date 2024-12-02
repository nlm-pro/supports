# Création et intégration de web components pour applications mobile et multi-plateformes

## Objectifs

En fin de cours, l'élève doit avoir atteint les objectifs suivants :

- Comprendre les Web Components
- Comprendre comment utiliser Stenciljs pour générer des composants Web et des applications Web progressives (PWA)
- Mettre en œuvre les applications multi-plateforme
- Intégration avec Angular, React et VueJS.
- L’intégration mobile dans le développement des Web Components

## Programme de la formation

1. [Web Component : créer des composants Web autonomes et réutilisables](./01-standards.html)
   1. La norme des Web Components.
   1. Rappels DOM & AJAX.
   1. Template HTML à chargement différé.
   1. Shadow DOM, et CSS, les fragments de documents.
   1. CSS : le besoin d'encapsulation.
   1. Custom Elements.
   1. [**_EXERCICES_**](./exercices/EX01-standards.md) & [correction](./exercices/corrections/1-1.html)
2. [StencilJS le compilateur de Web Component proposé par Ionic](./02-stenciljs.html)
   1. Présentation de Stencil
   1. Premiers pas avec les composants Stencil
   1. Propriétés, méthodes et gestion de l’état des composants
   1. Gestion des évènements et interactions utilisateur
   1. Routage
   1. Formulaires
   1. Service Workers
   1. Introduction à LIT Web Component Library, une bibliothèque simple qui permet de créer des composants Web légers et rapides
   1. [**_EXERCICES_**](./exercices/EX02-stencil.md)
3. Réutilisation des composants cross-frameworks
   1. Développement de composants "cross-plateformes/cross-projet"
   1. Intégration avec Angular, React et VueJS
   1. Encapsuler son code Angular avec Angular Elements
   1. Créer des Web Components avec React
   1. Alléger son code React avec Preact
   1. L'intégration dans Vue.js
   1. [**_EXERCICES_**](./exercices/EX03-interop.md)

### Conclusion

> Analyse d’un cas concret dans le contexte de l'entreprise

- Analyse « critique »
- Retour d’expérience
- Revue des best practices
- Proposition d’architecture du code

## Liens

- [Nommer un élément personnalisé](https://fullweb.dev/fr/tools/ce-name)
- [Mozilla Standards Positions](https://mozilla.github.io/standards-positions/)
- [es6-string-html VS Code extension](https://marketplace.visualstudio.com/items?itemName=Tobermory.es6-string-html)
- [web.dev - declarative shadow DOM](https://web.dev/articles/declarative-shadow-dom)
- [WHATWG - HTML: The Living Standard, Edition for Web Developers](https://html.spec.whatwg.org/dev/)
- [exemple HyperScript](https://codesandbox.io/p/sandbox/github/fullwebdev/fullwebdev/tree/master/demos/helpers/el-simple-counter)
    - [sur GitHub](https://github.com/fullwebdev/fullwebdev/tree/master/demos/helpers)
    - [code source du helper el](https://github.com/fullwebdev/fullwebdev/blob/master/packages/helpers/el/index.js)
- [MDN Web docs - Web Components](https://developer.mozilla.org/en-US/docs/Web/API/Web_components)