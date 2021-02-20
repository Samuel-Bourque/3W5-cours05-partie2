# Réalisation

## Intégration du frontend au backend de manière automatisée

- Pipeline à 2 étapes;
  - Checkout du backend et tests unitaires. Il faudra mettre un test unitaire dans votre backend pour faire fonctionner cette opération.
  - intégration du frontend au backend
    - Checkout des deux _repositories_ en commandes git
    - Déplacement du répertoire courant dans le frontend (note: nouveau processus à chaque commande)
    - Installation des paquets npm
    - Build de l'application frontend (npm run build)
    - Retour arrière du répertoire courant
    - Copie du répertoire de build du frontend dans le backend, comme fait au cours 3
    - Déploiement sur amazon (fictif: echo "déploiement", voir AWS CLI)
