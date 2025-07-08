# Architecture 3-Tiers

## Définition

L’architecture 3-Tiers (ou N-Tier) est une architecture logicielle qui sépare une application en trois couches logiques distinctes. Cette séparation permet une meilleure organisation du code, une maintenance facilitée et une évolutivité plus simple.

## Les trois couches

### 1. Couche de présentation (Presentation Layer)
- Gère l’interface utilisateur.
- Affiche les données et récupère les interactions.
- Exemple : pages HTML, interfaces graphiques, applications mobiles.

### 2. Couche métier (Business Logic Layer)
- Contient les règles de gestion et la logique métier.
- Traite les données reçues ou à envoyer.
- Exemple : validations, calculs, logique de traitement.

### 3. Couche d’accès aux données (Data Access Layer)
- Gère l’interaction avec la base de données.
- Effectue les requêtes SQL, les insertions, mises à jour, suppressions.
- Exemple : DAO (Data Access Object), ORM.


