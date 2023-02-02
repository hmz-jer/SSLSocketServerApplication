# SSLSocketServer

Ce projet est une application Spring Boot qui implémente un serveur de socket SSL pour rester à l'écoute des clients et répondre sous forme de fichier XML en utilisant un fichier externe.
Prérequis

    Java 8 ou plus récent
    Gradle 6.0 ou plus récent

Installation

    Clonez le projet depuis ce dépôt GitHub.
    Accédez au répertoire du projet à l'aide de la ligne de commande.
    Exécutez la commande gradle build pour construire le projet.
    Configurez le numéro de port et les chemins vers le trustore et le keystore dans le fichier de configuration.
    Exécutez la commande gradle bootRun pour démarrer l'application.

Utilisation

L'application peut être contrôlée en utilisant les commandes suivantes :

    start : commence l'écoute du client.
    stop : arrête l'application.
    status : affiche le statut actuel de l'application.

Licence

Ce projet est sous licence MIT.
