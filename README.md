# Atelier Portfolio
Développe et déploie ton portfolio en quelques minutes, tu pourras ensuite le faire évoluer à ton rythme

📚 À cette occasion, vous utiliserez :
- Un soupçon de HTML
- la magie de Boostrap
- les bases de Git
- GitHub et GitHub Pages

## Prérequis :
Git : https://git-scm.com/downloads

## Création du dépôt Git
### 1. Créez un dépôt (repository) distant sur GitHub
Connectez-vous sur votre compte GitHub et créez un nouveau dépôt public nommé my_username.github.io,my_username correspondant à votre nom d'utilisateur sur GitHub.

### 2. Publiez votre premier "Hello World"
Directement depuis l'interface graphique de GitHub, ajoutez un fichier index.html et insérez le code HTML suivant \<h1>Hello World !\</h1>
Allez en bas de page pour "enregistrer" votre première contribution (dans le jargon de Git, on dit faire un commit).
GitHub nous suggère un message de commit, il décrit parfaitement votre action, gardez-le en l'état et commitez ce nouveau fichier grâce au bouton vert.

Une fois le processus terminé avec succès, rendez-vous sur https://my_username.github.io

🎉 FÉLICITATIONS, votre code a été déployé.

Maintenant, il est temps d'étoffer cette page index.html

3. Récupérez votre dépôt en local
En local, ouvrez un terminal et placez-vous à l'endroit où vous souhaitez cloner votre dépôt distant.

git clone https://github.com/my_username/my_username.github.io
cd my_username.github.io
Visualisez votre tout premier commit avec la commande git log :

git log
4. Mise en forme avec Bootstrap
Pour poursuivre le travail, vous allez vous baser sur l'un des thèmes gratuitement proposé ici par Bootstrap.

Précisément, nous allons télécharger les ressources du thème resume 📥

À noter

Ici prenez bien le temps d'observer le descriptif du thème, de vous rendre sur cette autre page pour comprendre son comportement et les possibilités offertes. Ensuite, n'hésitez pas à faire de même avec les ressources téléchargées, c’est-à-dire l'ensemble du code et les éléments graphiques.

Décompressez l'archive, copiez son contenu, à savoir le fichier index.html et les répertoires assets, css et js, puis copiez-les dans le dossier my_username.github.io précédemment créé.

À noter

👉 Un fichier index.html existe déjà, votre système d'exploitation devrait vous en alerter. Il s'agit de celui comprenant notre "Hello World", Pas de souci, vous pouvez l'écraser au profit de ce nouveau fichier.

Dans votre terminal, placez-vous dans ce dossier et effectuer ces commandes :

git add --all 
git commit -m "init Boostrap theme"
git push -u origin main
Ces commandes permettent :

D'intégrer les nouveaux éléments du thème au dépôt local.

De les regrouper sous le commit "init Boostrap theme".

De les transmettre à votre dépôt distant hébergé sur votre compte GitHub.

Sur votre compte GitHub, replacez-vous dans l'onglet "Actions" afin de visualiser le build et le déploiement en cours. Une fois terminé, rendez-vous sur https://my_username.github.io

🎉 FÉLICITATIONS, votre thème a été déployé.
