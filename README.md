# Application de Playlist Musicale

Bienvenue dans l'application de Playlist Musicale "MDSongs". C'est une application en ReactJs qui a été conçue dans le cadre du cours Framework JS dispensé par Aurelien BOIS à MyDigitalSchool Toulouse. Le but a été de faire une surprise à nos camarades de classe en générant une musique amusante sur eux.


Merci à toutes les personnes de loin ou de près qui nous ont aidé à avoir ce résultat.

## Architecture de l'Application

L'application est développée en utilisant ReactJS et suit une structure bien organisée pour améliorer la lisibilité et la maintenance du code. Voici un aperçu de l'architecture :

- **Composants :** Les différents composants de l'application sont séparés dans des fichiers individuels pour favoriser la modularité. Les composants principaux incluent `Homepage`, `OneSong`, et `SongPlayer`.

- **Fournisseurs de Contexte :** Les fichiers liés aux fournisseurs de contexte, tels que `SongContextProvider` et `SongsContext`, sont regroupés dans un dossier "providers". Ces contextes sont utilisés pour gérer l'état global de l'application.

- **Données des Chansons :** Les données des chansons sont stockées dans le fichier `sons.js` dans un dossier distinct. Cela sépare les données de l'application de la logique des composants.

- **Ressources :** Les images et les fichiers audio sont organisés dans des dossiers distincts sous "assets"



## Instructions de Déploiement

1. Clônez le projet depuis le dépôt GitHub.
2. Installez les dépendances en utilisant `npm install`.
3. Ajoutez des chansons à la collection "songs" de Firestore dans la console Firebase.
4. Lancez l'application avec `npm start`.

