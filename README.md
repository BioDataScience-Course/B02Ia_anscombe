# Module 2 Régression linéaire II - Découverte du jeu de données artificiel "anscombe"

## Avant-propos

Cette séance d'exercices peut évoluer. N'hésitez pas à vérifier le lien suivant afin de voir si des modifications n'ont pas été apportées dans les consignes : https://github.com/BioDataScience-Course/B02Ia_anscombe

## Objectifs

Ce projet est un projet **individuel**, **court** et **cadré** qui doit être **terminé pour la fin du module 2**. 

- Être capable d'interpréter les informations fournies par la fonction `summary()` appliquée à un objet `lm`.
- Pouvoir interpréter les outils de diagnostic de la régression linéaire correctement.

**Il s'agit ici d'un jeu de données artificiel créé pour vous faire prendre conscience qu'une analyse détaillée d'un corrélation ou d'une régression est indispensable, en particulier, la visualisation des données et l'analyse graphique des résidus.** Ne tentez pas d'analyser plus à fond ces données (transformations, élimination de valeurs extrêmes, ...). Oui, il y a des cas pathologiques, et non, toutes les régressions ne sont pas valables ici. Tout ce qu'on vous demande, c'est de l'observer et d'exercer votre œil à identifier de telles problèmes pour ne pas vous faire avoir plus tard sur de *vraies* données qui présenteraient les mêmes problèmes.

## Consignes 

Au sein du fichier `anscombe.Rmd`, qui se trouve dans le dossier `docs` : 

- Importez le jeu de données `anscombe` depuis le package {datasets}. 

- Réalisez un graphique pour chacune des combinaisons suivantes et assemblez ces graphiques individuels sur une même figure :
    + `y1 ~ x1`
    + `y2 ~ x2`
    + `y3 ~ x3`
    + `y4 ~ x4`

- Calculez les coefficients de corrélation pour chaque paire de variables *xi* - *yi*

- Ensuite, pour chaque paire de variables *xi* - *yi* :
    + réalisez une régression linéaire
    + analysez et commentez le tableau de résultats
    + analysez les résidus, sélectionnez 3 graphiques intéressants parmi les 6 vus au cours et commentez-les succinctement. 

- Terminez par une conclusion générale.
