# WebContent Project

Le MVC dans ce projet :

## Le modèle : la map d'attribut que tu crée dans la classe GreetingController
En utilisant l'Objet Model de springFramework tu crée une map (association clé: valeur) dans laquelle tu mets name = valeur (default = world)

## La vue : les fichiers html dans les ressources.
Tu utilises un framework nommé Thymleaf qui te permet simplement de mapper des objets java dans ta vue.

## Le controlleur : la classe GreetingControlleur.
C'est elle qui décide de faire des actions lorsqu'on tappe sur l'url /greeting, elle alimente le modèle et le passe à la vue (dont le nom est dans la String retournée). C'est l'utilisation de Thymeleaf qui permet de rendr eles choses aussi simple. 

<3
