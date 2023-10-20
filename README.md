# DeliveCROUS

## Auteurs
- Tom BERANGER (dev back / front)
- Thomas CAZIN (dev front)
- Bastien LEMARIÉ (dev back)

## Description
Le but de ce projet est de créer une application cross-plateform permettant de faire une commande de repas. Nous avons plusieurs écrans :

- **Liste des plats** : Cet écran répertorie les plats proposés avec une image du produit (non contractuelle), un titre, une description, un prix, une catégorie et toute autre information pertinente. Il offre la possibilité de filtrer les plats par catégorie (végé, viandard, healthy, gras, etc.) et de les rechercher. Les utilisateurs peuvent ajouter des plats au panier depuis cet écran.

- **Détail du plat** : Cet écran affiche les détails du plat sélectionné précédemment, y compris les allergènes. Les utilisateurs peuvent également ajouter ce plat au panier depuis cet écran.

- **Panier** : L'application propose un système de panier, où un récapitulatif des plats sélectionnés est présent. Les utilisateurs peuvent modifier la quantité des plats souhaités et les supprimer du panier. Ils peuvent également renseigner l'adresse de livraison et valider la commande.

- **Écran de succès** : Cet écran confirme que la commande a bien été prise en compte.

## Configuration

### Frontend
- Utilisation de React Native pour sa réactivité, son large écosystème de bibliothèques et de ressources, ainsi que sa facilité d'apprentissage.
- Inconvénients : Les mises à jour fréquentes de React Native peuvent entraîner des problèmes de compatibilité, et la configuration requise peut être complexe.

### Backend
- Utilisation de Java avec Spring Boot pour créer une API REST conformément aux spécifications du projet.
- Utilisation d'une base de données H2 embarquée, conforme aux exigences du projet.

## Architecture Backend
- `src\main\java\...\entities\` : Contient les classes d'entités Spring Boot.
- `src\main\java\...\resources\` : Contient les classes avec les endpoints de l'API Spring Boot.
- `src\main\java\...\services\` : Contient les classes utilisées dans les ressources pour les fonctions de l'API.
- `src\main\java\...\repository\` : Contient les classes utilisées dans les services pour stocker les données dans la base de données et effectuer des requêtes SQL si nécessaire.

## Lancement du Projet
Pour lancer le projet, exécutez la classe `DemoApplication.java`.

## Logiciels Utilisés
- VSCode pour la programmation.
- Firefox pour accéder à H2, tester l'API et le site web.
- Postman pour tester toutes les requêtes API.

## Ressources Supplémentaires
- [Lien du GitHub](https://github.com/orgs/framework-ttb/)
- [Lien vers la documentation de l'API](http://localhost:8080/swagger-ui/index.html#/).
- [Lien de la base de données H2](http://localhost:8080/h2/)
  - driverclass: org.h2.Driver
  - JDBC URL: jdbc h2:~/demo
  - utilisateur: TOMTHOMASBASTIEN
  - mot de passe : bonjour
  - **conseil : pour le bon fonctionnement du projet supprimer votre ancienne bdd h2 si l'url est la même**
- [Lien du projet Postman](https://delivecrous.postman.co/workspace/New-Team-Workspace~26a00c14-d4b7-4683-b4c8-0b008900cf41/collection/29512453-3f0e4334-75a6-41f3-8e50-223888663dac?action=share&creator=29512453)

N'hésitez pas à explorer notre projet et à nous contacter pour toute question ou suggestion.
- lemariebast@gmail.com
- thomas.cazin16@gmail.com
- tomberanger01@gmail.com
