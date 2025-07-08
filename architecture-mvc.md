# Architecture MVC (Model-View-Controller)

## Définition

MVC est un modèle d’architecture qui permet de séparer une application en trois parties indépendantes. Très utilisé pour les applications web et desktop, il favorise la maintenabilité et la testabilité.

## Composants

### 1. Modèle (Model)
- Gère les données et la logique métier.
- Communique avec la base de données.
- Exemple : objets, entités, services.

### 2. Vue (View)
- Gère l'affichage et la présentation des données.
- Ne contient aucune logique métier.
- Exemple : fichiers HTML, templates, interfaces graphiques.

### 3. Contrôleur (Controller)
- Intercepte les actions de l’utilisateur.
- Met à jour le modèle ou la vue en conséquence.
- Exemple : routes, gestionnaires d’événements.

## Flux de données
```bash 
[ Utilisateur ]
     |
[ Contrôleur ]
     |
[ Modèle ] ---> [ Vue ]
```