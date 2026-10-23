# Programme de Prédication

Application web autonome et légère pour la planification, la gestion et l'impression du programme mensuel des réunions pour la prédication.

## Fonctionnalités

- **Configuration de l'assemblée** :
  - Nom de l'assemblée et lieu par défaut (Salle du Royaume).
  - Gestion flexible des cartes de territoire (lettres + chiffres ou chiffres seulement, plages personnalisables).
  - Configuration libre des groupes de prédication et de leurs lieux habituels de rendez-vous.
  - Sélection des jours de réunion pour la prédication dans la semaine.

- **Gestion des données** :
  - Liste des présidents / conducteurs.
  - Thèmes et matières pour les réunions.
  - Lieux de rendez-vous récurrents.
  - Stockage local sécurisé dans le navigateur avec IndexedDB (Dexie.js).

- **Édition et génération mensuelle** :
  - Génération automatique des semaines du mois.
  - Attribution des présidents, matières, territoires et lieux de rendez-vous par groupe et par jour.
  - Générateur automatique pour répartir les territoires et matières.

- **Mise en page d'impression** :
  - Rendu haute fidélité au format A4 paysage.
  - Prêt pour impression directe ou exportation en PDF.

- **Système de Sauvegarde et Restauration** :
  - **Exportation complète** : Téléchargement d'un fichier JSON sécurisé contenant la configuration, les listes et tous les plannings enregistrés.
  - **Restauration flexible** :
    - Mode remplacement complet (restauration miroir propre).
    - Mode fusion intelligente (enrichit les listes et plannings existants sans écraser).
    - Zone de glisser-déposer (Drag & Drop) et aperçu préalable des données avant confirmation.
  - **Instantanés rapides locaux (Snapshots)** : Historique de sauvegarde instantanée dans le navigateur pour revenir en arrière en 1 clic.
  - **Réinitialisation sécurisée** : Remise à zéro complète avec mot de confirmation.

## Utilisation

Ouvrez simplement le fichier `index.html` dans un navigateur web moderne. Aucune installation ou serveur backend n'est requis.
