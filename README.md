# Démarrage de site statique simple

Ce modèle permet de démarrer un site statique qui peut être lancé en local avec la commande `vite`.

Quand il est stocké dans un dépôt Github ou Gitlab, un site statique est publié.

Le contenu présent dans le dossier `public` sera déployé automatiquement en ligne à chaque fois que du code est poussé avec `git push`.

<img width="789" height="344" alt="image" src="https://github.com/user-attachments/assets/bb267ded-8a90-46db-b794-8a9ee0c835bb" />

[Publier un site statique en 3 minutes avec Github Pages](https://www.youtube.com/watch?v=zeROcSDESe8)

## Utiliser ce template avec Github.

Se rendre sur https://github.com/coda-school/template-site-statique.
Cliquer sur le bouton `Utiliser ce template` puis `Créer un nouveau dépôt`.

Donner un nom et une description au dépôt.
Choisir la visibilité `public`.

### Déploiement sur Github pages

Le dépôt doit avoir la visibilité `public`

Dans les `paramètres` du dépôt, rubrique `Pages`, positionner la source de déploiement à `Github Actions`.

### Afficher le lien de la page dans Github

Revenir à la page principale du dépôt Github.

Dans la rubrique `à propos` (à droite), passer en mode edition.

Dans la rubrique site Web, cocher `Utiliser votre site Web Github Pages`.

Sauvegarder les changements.

L'adresse du site est maintenant affichée dans la rubrique `à propos`.

## Utiliser ce template avec GitLab.

Lors de la création d'un nouveau dépôt, choisir l'option `importer un projet`.

Choisir `Dépôt par URL`.

Pour `URL du dépôt Git`: `https://github.com/coda-school/template-site-statique.git`

Donner un nom au dépôt.

Idéalement, rendre le projet public.

Créer le projet.

Le site devrait se déployer la prochaine fois qu'un fichier est `git push`.

### Rendre le site public à tous

- Paramètres
  - Général
    - Visibilité, fonctionalité projet et permissions
    - Pages : "Tout le monde"
    

## Lancer le serveur en local avec vite

Après avoir rempli les prérequis (voir plus bas).

Dans une ligne de commande:
```shell
npx vite public
```

Ou si vous avez installé vite globalement
```shell
vite public
```

Ouvrir dans le navigateur : http://localhost:5173

## Prérequis

### Installer nodejs

Installer nodejs : https://nodejs.org/fr/download

### (Optionnel) installer vite globalement

Installer la commande `vite`

Dans une ligne de commande:
```shell
npm install -g vite
```

