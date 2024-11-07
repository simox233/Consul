Migration de Eureka vers Consul

Ce projet se concentre sur la migration de microservices utilisant Eureka vers Consul. L'objectif est de moderniser l'infrastructure de découverte de services en intégrant Consul, un outil open-source développé par HashiCorp, qui apporte des fonctionnalités avancées de découverte de services, de gestion de configuration et de segmentation réseau.

Étapes de la Migration

Vérification Locale des Projets

Clonez les projets depuis le dépôt Git ms-arch-TP1.
Exécutez les microservices localement pour vérifier leur bon fonctionnement avant de commencer la migration.
Configuration et Démarrage de Consul

Téléchargez la version la plus récente de Consul depuis le site officiel.
Décompressez le fichier téléchargé dans un répertoire dédié, par exemple C:\consul.
Ajoutez le chemin de ce dossier dans la variable d'environnement PATH pour faciliter l'accès à Consul via la ligne de commande.
Lancez Consul en mode développement en utilisant la commande suivante :
shell
Copier le code
consul agent -dev
