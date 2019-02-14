# POPCORN-MORBIHAN 🍿

_Popcorn_ est une plateforme open source et (vraiment) sans frais ni commission initié par [Popcorn-Nantes](https://github.com/popcorn-nantes/popcorn-nantes) qui aide les développeur-e-s freelance à trouver des projets.

[Popcorn-Morbihan](https://popcorn-morbihan.github.io/) est un fork de ce projet pour les développeur-e-s freelance du Morbihan !

Les objectifs de _Popcorn-Morbihan_ pour les développeurs freelances :

- 📈 Etre un canal pour trouver des affaires sans commission ni intermédiaire.
- 📗 Maitriser les fonctionnalités de la plateforme en contribuant à [la machine à Popcorn](https://github.com/popcorn-nantes/popcorn-machine).
- 💬 Faire circuler les tuyaux boulot entre freelances. Pour cela il vous suffit de vous inscrire au groupe meetups de [Vannes Software Development](https://www.meetup.com/fr-FR/Vannes-Software-Development/?_locale=fr-FR). Vous receverez alors une invitation au slack du même nom et à son chan `popcorn` !
- 💪 Offrir une alternative locale aux _market places_ de freelances centralisées

## Créer son profil

- Fork ce dépôt
- Déplace-toi dans la branche draft `git checkout draft`
- Ajoute ta fiche dans le dossier `content/persons` en prenant comme exemple le fichier `_example.md`. Le nom de ton fichier sera utilisé pour créer l'url de ton profil.
- Ajoute ta photo dans le dossier `/public/images/photos` : **la photo doit faire 100ko maximum ⚠️**
- Fait une _pull request_ avec pour titre _Nouveau profil : {ton prénom}_ .
- Bienvenue sur _Popcorn_ !

Pour soumettre une suggestion, signaler un bug, demander de l'aide, tu peux aussi tout simplement [ouvrir une issue sur ce repo](https://github.com/popcorn-morbihan/popcorn-morbihan/issues/new)

## Installation

cloner ce dépôt puis

```sh
npm install
```

démarrer le serveur de dev

```sh
npm run dev
```

Générer la version statique du site

```sh
npm run generate
```

### Déployer

1. merger la branche `draft` dans la branche `master`
2. `git push`

Le déploiement du site est déclenché automatiquement par _Travis_ lors d'un _push_ sur la branche `master`. Il peut prendre quelques minutes avant d'être visible en production.
