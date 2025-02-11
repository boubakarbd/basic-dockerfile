# Docker Hello Captain Project

L'URL du projet GitHub est : [https://github.com/boubakarbd/basic-dockerfile](https://github.com/boubakarbd/basic-dockerfile).

Ce projet consiste à créer une image Docker simple qui affiche "Hello, Captain!" dans la console avant de se terminer.

## Instructions

1. **Dockerfile** : Le fichier Dockerfile doit être nommé `Dockerfile` et doit être placé à la racine du projet.
2. **Image de base** : L'image de base utilisée est `alpine:latest`.
3. **Commande** : Le Dockerfile doit contenir une seule instruction pour afficher "Hello, Captain!" dans la console avant de se terminer.

## Structure du projet
.
├── Dockerfile
└── README.md

Construction et exécution de l'image Docker

Pour construire l'image Docker, exécutez la commande suivante à la racine du projet :
docker build -t hello .

Pour exécuter l'image Docker et afficher le message, utilisez la commande suivante : docker run hello

Résultat attendu

Lorsque vous exécutez l'image Docker, vous devriez voir le message suivant dans la console : Hello, Captain!