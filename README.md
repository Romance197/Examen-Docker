# Examen-Docker
# Guide des Commandes de bases Docker

Ce document regroupe les commandes Docker les plus utiles pour gérer des conteneurs, images, volumes, et réseaux.

# Vérifier l'installation
docker --version

# Visualiser ou lister les conteneurs actifs
docker ps
 
# visualiser ou lister tous les conteneurs
docker ps -a

# Supprimer un conteneur inactifs
docker rm [conteneur]

# forcer la suppression d'un conteneur actif
docker rm -f [conteneur]

# Arrêter un conteneur
docker stop [conteneur]

# Redémarre un conteneur
docker start 

# Construire un image à partir d'un Dockerfile
docker build -t [image]

# Lister les images locales
docker images

# Supprimer une image
docker rmi [image]

# Lancer un conteneur (interactif)
docker run -it [image]

# Lancer un conteneur en arrière-plan
docker run -d [image]

# Récupérer une image 
docker pull [image]

# Rechercher une image 
docker search

# Créer un volume
docker volume create [volume]

# Lister les volumes
docker volume ls

# Supprimer un volume
docker volume rm [volume]

# Lister les réseaux
docker network ls

# Créer un réseau
docker network create [reseau]

# Supprimer un réseau
docker network rm [reseau]

# Supprimer les conteneurs, réseaux, images inutilisés
docker system prune

# Nettoyer uniquement les images non utilisées
docker image prune
