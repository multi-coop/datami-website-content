---
title: De l'importance de Git pour gérer les contributions aux données
tags: 
  - contribution
  # - tech
  # - benchmark
  # - business model
  # - dataviz
  - edition
  # - ideas
  # - R&D
  - Git
  # - legal
  - interoperability
  # - open data
created: 30/03/2023
author: Julien Paris
---

Git est un système de contrôle de version qui permet de suivre l'historique des modifications d'un projet, ce qui facilite le travail en équipe et le suivi des changements. Cependant, Git ne se limite pas seulement aux développeurs de logiciels : il peut également être utilisé pour gérer des projets de données. 

Datami, notre widget de datavisualisation, utilise Git pour permettre aux utilisateurs de contribuer aux données. Avec Git, les utilisateurs peuvent facilement créer des branches pour travailler sur des modifications de données, puis proposer des changements pour être fusionnés dans le projet principal. Cela permet une collaboration décentralisée et garantit l'intégrité des données en gardant une trace de toutes les modifications apportées. Git facilite également la gestion des conflits de fusion, qui surviennent souvent lorsque plusieurs utilisateurs travaillent simultanément sur les mêmes données. Avec Datami, les utilisateurs peuvent facilement gérer les contributions apportées aux données, de façon à la fois efficace et transparente.

Git permet de travailler en parallèle sur différentes versions d'un même code, en créant des branches. Mais comment fonctionnent ces branches, et comment s'y retrouver lorsque l'on débute sur Git ?

Tout d'abord, il faut comprendre que Git est un système distribué, c'est-à-dire que chaque développeur dispose d'une copie complète du code source sur sa machine. Lorsqu'un développeur souhaite modifier le code, il crée une branche qui permet de travailler en parallèle sur cette modification, sans impacter le code principal. Une fois les modifications apportées, le développeur peut les intégrer à la branche principale, ou les fusionner avec une autre branche.

Le processus de création d'une branche commence par la commande "git branch nom-de-la-branche". Cette commande crée une nouvelle branche à partir de la branche courante. Il est conseillé de nommer la branche de manière explicite, pour pouvoir s'y retrouver facilement.

Une fois la branche créée, le développeur peut commencer à travailler sur cette branche en effectuant des modifications sur les fichiers du projet. Pour voir les modifications apportées à la branche, le développeur peut utiliser la commande "git diff" qui affiche les différences entre les fichiers de la branche courante et ceux de la branche principale.

Lorsque le travail sur la branche est terminé, il est temps de fusionner les modifications avec la branche principale. Pour cela, le développeur peut utiliser la commande "git merge nom-de-la-branche". Cette commande fusionne les modifications de la branche avec la branche courante. Si des conflits sont détectés entre les deux branches, Git les signale au développeur qui doit alors les résoudre manuellement.

En résumé, Git permet de travailler en parallèle sur différentes versions d'un même projet grâce aux branches. Chaque branche permet de travailler sur une modification spécifique sans impacter le code principal. Une fois le travail sur la branche terminé, les modifications peuvent être fusionnées avec la branche principale.

Pour s'y retrouver dans les différentes branches, il est conseillé de nommer les branches de manière explicite, et d'utiliser des outils de visualisation graphique comme GitKraken ou GitLab pour avoir une vue d'ensemble des différentes branches et des modifications apportées. Il est également important de communiquer avec les autres membres de l'équipe pour éviter les conflits et assurer une bonne collaboration.