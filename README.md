# Examen-Docker
# Guide des Commandes Docker

Ce document regroupe les commandes Docker les plus utiles pour gérer des conteneurs, images, volumes, et réseaux.

# Vérifier l'installation
docker --version

# Visualiser ou lister les conteneurs actifs
docker ps
 
# visualiser ou lister tous les conteneurs
docker ps -a

# Supprimer un conteneur inactifs
docker rm[conteneur]

# forcer la suppression d'un conteneur actif
docker rm -f [conteneur]

# Arrêter un conteneur
docker stop nom_conteneur
