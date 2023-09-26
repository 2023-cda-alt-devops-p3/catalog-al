[https://catalog-al.netlify.app/](https://catalog-uml-merise.netlify.app/)

# Critères d'évaluation

## _Git_

- [x] Versionné régulièrement et de manière atomique (Plusieurs "commit" par jour pendant toute la durée du projet) => Vérif Git
- [ ] Historique de commit propre => (éviter les doublons, les commits inutiles)
- [x] Mise en place d'une branche de développement supplémentaire, voire plusieurs selon l'architecture du site => Vérif sur Git
- [x] Fonction "pull request" => Check sur Github
- [ ] Mise en place un Github Action (automatisation de tests intégration, vulnérabilité, ...) => Check sur Github

## _Sécurité_

- [ ] Prévenir les vulnérabilités principales (cross site, injection sql, protection des tokens, validation des données) => GoogleSearchConsole, Sucuri
- [ ] Respect de la protection des données (RGPD, encapsulation)
- [ ] Utilisation des chemins absolus

## _SEO_

- [ ] Mise en place de la stratégie SEO : données structurées, ...
- [ ] PWA (Progressive Web App) : services workers (microphone, localisation, ...)
- [x] HTML sémantique

## _Performance_

- [ ] Bon résultat sur PageSpeed Insights
- [x] Optimisation images (surtout mobile)
- [x] Limiter le nombre de requêtes

## _Accessibilité_

- [x] Accessibilité : title, aria-label, alt
- [x] Optimisation des images : poids et formats adaptés
- [x] Fournir un site web avec une bonne expérience utilisateur
- [x] Texte lisible : interlinéage suffisant, taille des polices proportionnelles, contraste des couleurs optimale, ...

## _Architecture_

- [x] Bons principes de structuration respectés, y compris pour le web mobile => vérif des balises (body, header, navbar), et des noms de classes CSS, variables, media queries
- [x] Eviter les répétitions en utilisant des fonctions => check du code source

## _Contenu_

- [x] Contenu vérifié : informations croisées, résumé de plusieurs sources, ...
- [x] Détail des étapes pour chaque diagramme

## _UI/UX_

- [x] Features d'animations, transitions, barre de navigation => vérif du site
- [x] Design cohérent (couleur, forme, police)
