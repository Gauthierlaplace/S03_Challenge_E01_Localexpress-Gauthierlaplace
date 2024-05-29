# Cahier des charges

**Société**  localexpress

**Objectif** faire de la livraison de courses à domicile

## Description 

Nous voulons une application web qui permet de commander des produits et de se faire livrer à domicile. Nous ne vendons que quelques produits, qui changent chaque semaine. Il n'est pas nécessaire d'avoir d'historique de commande.

Pour nous démarquer, nous souhaitons :

- Une interface simple, sans navigation. Les produits sont tous sur la même page, simplement rangés par catégories (a-z).
- Compatible smartphone
- Nous privilégions le contact humain
    * paiement à la livraison
    * facture papier (non gérée par l'application)
    * le livreur fera du teasing sur les produits à venir

Nous n'avons pas de contrainte sur la technologie utilisée. Il nous faudra juste un back-office pour gérer les produits et voir les commandes.

## Interface

Voici une idée de l'interface que nous imaginons. Nous ne sommes pas designers, donc n'hésitez pas à nous proposer des améliorations, car nous aimons vos réalisations.

Page d'acceuil :

![alt text](assets/w1.png)

Page de sélection des produits :

![alt text](assets/w2.png)

Détail d'un produit :

![alt text](assets/w3.png)

Finalisation d'une commande :

![alt text](assets/w4.png)

Commande validée :

![alt text](assets/w5.png)

## Maquettes et zonage

Page principale :

![alt text](maquettes/main_page.png)

Version mobile : 

![alt text](maquettes/main_mobile.png)

Page produit :

![alt text](maquettes/product_page.png)

Page produit mobile :

![alt text](maquettes/product_page_mobile.png)

Panier mobile :

![alt text](maquettes/cart_mobile.png)

## Conception

### User stories

|  En tant que     |  Je veux     |  Afin de     |
|---    |:--    |--    |
|Utilisateur| voir tous les produits disponibles sur une seule page||
|Utilisateur|  ajouter des articles au panier     ||
|Utilisateur|modifier la quantité d'un article dans le panier||
|Utilisateur|supprimer un article du panier||
|Utilisateur|vider le panier||
|Utilisateur|renseigner ses infos de livraison||
|Utilisateur|valider la panier pour commander||
|Administrateur|recevoir les détails des commandes et les informations de livraison|préparer et livrer les courses aux clients|
|Administrateur|ajouter de nouveaux produits dans le back-office|ajouter de nouveaux produits dans le back-office|
|Administrateur|modifier ou supprimer des produits existants|maintenir une liste de produits à jour et pertinente|


### Cas d’utilisation

![alt text](uml/usecases.png)

### Diagramme d’entité-association

![alt text](uml/erd.png)

### Diagramme de séquence

![alt text](uml/SequenceDiagram.png)

### Diagramme d’activité

![alt text](uml/activityDiagram.png)

### Diagramme de déploiement

TODO

### Schéma d'architecture

TODO
