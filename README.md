# Data Visualization Site

Ce projet est un site de visualisation de données en cours de développement, permettant d'afficher des données sous forme de graphiques.

## Statut du projet
MVP atteint (front et back développés, affichage de graphiques fonctionnel avec filtres temporels)
En cours de développement (améliorations design, message d'informations lorsqu'absence de data)

## Collaborateurs

Ce projet est un effort collaboratif non-scolaire, réalisé par deux membres :
- @annatehiva
- @realalexis

## Technologies utilisées

### Front-end
- **React**
- **Typescript**
- **Recharts.js** (pour les graphiques)

### Back-end
- **Spring Boot**
- **Hibernate** (pour l'API Rest)

### Base de données
- **PostgreSQL**

## Installation et lancement

### Prérequis
- Node.js
- npm
- Java JDK
- PostgreSQL

### Étapes pour lancer le projet

1. **Cloner le dépôt**
    ```bash
    git clone https://github.com/realalexis/AmyALexLifeSheet.git
    ```

2. **Configurer le back-end**
    - Configurer les paramètres de la base de données PostgreSQL dans le fichier `application.properties`.

3. **Lancer le back-end**
    ```bash
    cd api
    ```
    lancer le projet

4. **Installer les dépendances front-end**
    ```bash
    cd ../frontend
    npm install
    ```

5. **Lancer le front-end**
    ```bash
    npm run dev
    ```

## Utilisation

- Accédez à l'application via `http://localhost:5173` pour voir les graphiques de visualisation des données.
