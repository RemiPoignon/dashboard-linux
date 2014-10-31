# Dashboard-linux
Tableau de bord de vérification des ressources utilisées par votre serveur linux en temps réel.
Très simple à installer, il est développé en php et bash, il vous suffit de copier le répertoire dans votre répertoire www d'apache (ou de lui créer un VHost).

![screenshot](https://raw2.github.com/RemiPoignon/dashboard-linux/master/screenshot.png)

[Voir la documentation](http://remipoignon.github.io/dashboard-linux/)

## Fonctionnalité
* Jauge CPU utilisé
* Jauge RAM utile utilisé
* Jauge Espace disque utilisé
* Informations générales sur le serveur (nom, ip, uptime)
* Information sur le CPU (nombre de cœurs)
* Information sur la RAM (quantité max, utilisé, en cache, libre + SWAP)
* Information sur l'espace disque (max, utilisé, restant)
* Liste des utilisateurs connectés en ssh (utilisateurs, date de connexion, ip)
