[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tzO_JqWG)
- URL site WEB :  https://sae303-adam-couturier.netlify.app/
- URL Notebook Observable : https://observablehq.com/d/57dbab7637ba4d0d
- Nom : ADAM
- Prénom : Juline
- Nom binome : COUTURIER
- Prénom binome : Margaux

# Remarques :

Décrire ici les éléments techniques remarquables de votre site (interactions, navigation, responsive, accessibilité...).
Idéalement avec des liens vers votre site et/ou [votre code](https://github.blog/news-insights/product-news/relative-links-in-markup-files/)

Responsive design :
- Utilisation de Tailwind CSS avec DaisyUI pour un design entièrement responsive :
- Grilles adaptatives "(grid-cols-1 lg:grid-cols-2)" qui passent d'une à deux colonnes selon la taille d'écran
- Navigation fixe qui reste visible lors du scroll
- Graphiques avec "viewBox" et "max-width: 100%" pour s'adapter à tous les écrans

Traitement des données :
- Manipulation des données côté serveur dans le frontmatter Astro 
- Optimisation des performances en évitant les calculs côté client
- Création de cartes et graphiques depuis Observable pour représenter les données

Navigation et UX :
- Menu fixe avec fond semi-transparent pour un accès rapide à la conclusion
- Liens internes optimisés avec des chemins absolus pour éviter les problèmes de routage
- Système de couleurs cohérent : palette violette (#6D0E80, purple-900) utilisée dans tout le site
- Hiérarchie typographique claire avec des titres de différentes tailles "(text-4xl, text-2xl)"
- Call-to-action pour inviter l'utilisateur à naviguer sur le site
- Cards résumant les données pour avoir un accès simple et visuel des données présentées

Gestion des assets :
- Images optimisées placées dans le dossier public/ pour un accès direct
- Fichiers JSON de données dans src/assets/ pour l'import automatique par Astro

Accessibilité :
- Attributs alt sur toutes les images
- Contrastes de couleurs respectant les normes WCAG
- Structure sémantique HTML5 avec <nav>, <header>, sections clairement définies

Déploiement :
- Site déployé sur Netlify avec build automatique depuis le repository Git, garantissant des mises à jour continues et un hébergement performant