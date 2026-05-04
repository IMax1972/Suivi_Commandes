# 📦 Suivi Commandes

Application web **single-file** pour suivre vos commandes en attente de livraison.  
Aucune dépendance, aucun serveur — fonctionne directement dans le navigateur.

## Fonctionnalités

- **Suivi en attente** : cartes par commande avec nature du colis, plateforme, date prévue, adresse, référence de suivi et notes
- **Indicateurs de délai** : en retard / aujourd'hui / dans 3 jours / OK
- **Édition** : modification de toute entrée à tout moment
- **Réception** : archivage en un clic avec date de réception
- **Archives** : historique des commandes reçues, restauration possible
- **Paramétrage** : gestion des plateformes, points de livraison et natures de colis
- **Persistance** : données sauvegardées dans le `localStorage` du navigateur

## Utilisation

Ouvrir `suivi-commandes.html` dans un navigateur moderne. Aucune installation requise.

> Compatible Chrome, Firefox, Edge, Safari.

## Structure du projet

```
suivi-commandes/
├── suivi-commandes.html   # Application complète (HTML + CSS + JS)
├── README.md              # Ce fichier
└── .gitignore             # Fichiers exclus du dépôt
```

## Données

Les données sont stockées localement dans le navigateur (`localStorage`).  
Elles ne sont pas synchronisées entre appareils et sont perdues si le cache du navigateur est effacé.

## Licence

Usage personnel — tous droits réservés.
