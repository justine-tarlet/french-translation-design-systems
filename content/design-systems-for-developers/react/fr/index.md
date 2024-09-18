--- 
title : 'Design Systems for Developers' 
description : 'Découvrez comment construire et maintenir des systèmes de conception en utilisant Storybook' 
heroDescription : 'Un guide qui enseigne aux développeurs professionnels comment transformer les bibliothèques de composants en systèmes de conception et mettre en place l'infrastructure de production utilisée par les principales équipes frontales' 
overview : « Les systèmes de conception alimentent les équipes frontales de Shopify, IBM, Salesforce, Airbnb, Twitter et bien d'autres. 
Ce guide destiné aux développeurs professionnels examine comment les équipes les plus intelligentes conçoivent des systèmes de conception à grande échelle et pourquoi elles utilisent les outils qu'elles utilisent. Nous verrons comment mettre en place les services de base, les bibliothèques et les flux de travail pour développer un système de conception à partir de zéro. » 
order : 2 
themeColor : '#0079FF' 
codeGithubUrl : 'https://github.com/chromaui/learnstorybook-design-system' heroAnimationName : null 
toc : [ 'introduction', 'architecture', 'build', 'review', 'test', 'document', 'distribute', 'workflow', 'conclusion', ] 
coverImagePath : '/guide-cover/design-system.svg' 
thumbImagePath : '/guide-thumb/design-system.svg' 
contributorCount : '38+' 
authors : [ { 
  src : 'https://avatars2.githubusercontent.com/u/263385', name : 'Dominic Nguyen', detail : 'Storybook design', }, { src : 'https://avatars2.githubusercontent.com/u/132554', name : 'Tom Coleman', detail : 'Storybook core', }, ] contributors : [ { src : 'https://avatars2.githubusercontent.com/u/239215', name : 'Fernando Carrettoni', detail : 'Design Systems at Auth0', }, { src : 'https://avatars2.githubusercontent.com/u/8339031', name : 'Jessie Wu', detail : 'Ingénieur au New York Times', }, { src : 'https://avatars2.githubusercontent.com/u/21959607', name : 'John Crisp', detail : 'Ingénieur chez Acivilate', }, { src : 'https://avatars2.githubusercontent.com/u/1474548', name : 'Daniel Duan', detail : 'Ingénieur chez Squarespace', }, { src : 'https://avatars2.githubusercontent.com/u/85783', name : 'Kaelig Deloumeau-Prigent', detail : 'UX Development at Shopify', }, ] twitterShareText : « J'apprends à construire des systèmes de conception ! 
Ils sont parfaits pour la mise à l'échelle du code frontend au sein de grandes équipes. » 
---

<h2>
Ce que vous allez construire</h2>

<div class="badge-box">
  <div class="badge">
    <img src="/frameworks/logo-react.svg"> React
  </div>
  <div class="badge">
    Emotion
  </div>
  <div class="badge">
    Prettier
  </div>
  <div class="badge">
    GitHub Actions
  </div>
  <div class="badge">
    ESLint
  </div>
  <div class="badge">
    Chromatic
  </div>
  <div class="badge">
    Rollup
  </div>
  <div class="badge">
    npm
  </div>
  <div class="badge">
    Auto
  </div>
</div>

![Exemple de système de conception](/design-systems-for-developers/design-system-overview.jpg) Suivez-nous dans le codage d'un système de conception inspiré du [Storybook's own](https://medium.com/storybookjs/introducing-storybook-design-system-23fd9b1ac3c0). Nous découvrirons le point de vue des développeurs sur les systèmes de conception en examinant trois éléments techniques d'un système de conception. - 🏗 Composants d'interface utilisateur communs réutilisables - 🎨 Design tokens : Variables spécifiques au style, telles que les couleurs de la marque et l'espacement - 📕 Site de documentation : Après cela, nous mettrons en place l'infrastructure industrielle pour la révision, les tests, la documentation et la distribution.
