# Dashboard-linux
Tableau de bord de vérification des ressources utilisé par votre serveur linux en temps réel.
Simple à installer, juste un copier coller du répertoire dans un virtual-host apache.

## Fonctionnalité
* Jauge CPU utilisé
* Jauge RAM utile utilisé
* Jauge Espace disque utilisé
* Informations générale sur le serveur (nom, ip, uptime)
* Information sur le CPU (nombre de cœurs)
* Information sur la RAM (quantité max, utilisé, en cache, libre + SWAP)
* Information sur l'espace disque (max, utilisé, restant)
* Liste des utilisateurs connecté en ssh (utilisateur, date de connexion, ip)

## Installation
1. Télécharger le package
1. Créez un virtual-host Apache utilisant le dossier du package (ou copier le dans votre www).

## Support
* PHP 5 (commande shell_exec possible)
* Apache 2

## Test
Testé avec Ubuntu Server 13.4
