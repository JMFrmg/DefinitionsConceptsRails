# Explication des concepts fondamentaux de rails
<br />

Nous allons étiduer les points suivants :
1. La différence entre un site statique et un site dynamique
1. Le MVC
1. Les routes
1. Les bases de données
1. Get/POST
1. Le concept de migration
1. Les relations entre les models des BDD
1. Les fonctions du CRUD

<br />

## La différence entre un site statique et un site dynamique


La différence entre un site web dynamique un un site web statique est la technologie utilisée. Lorsqu'un navigateur internet envoie une requête vers un serveur http pour consulter une page web statique, le serveur se contente de renvoyer le contenu du fichier où la page est enregistrée. En revanche, lorsqu'une requête est envoyé vers un serveur http pour consulter une page web dynamique, le serveur va transmettre cette requête au logiciel qui va générer la page. Puis, le logiciel renvoie le contenu de la page au serveur. Le critère de distinction entre ces deux types de pages web est le moment où la page est générée.

#### Définitions :

Site statique : Page web dont le contenu est généré antérieurement à sa consultation.
Site dynamique : Page web dont le contenu est généré postérieurement à la requête de consultation.
<br />

## Le MVC

Le **MVC** (modèle vue contrôleur) est un patron d'architecture logicielle.Il ne désigne pas un langage de programmation C'est un modèle d'architecture logicielle type qui est très utilisée avec une multitudes de langages de programmation. Il est très utilisé dans la conception d'application web.
Le modèle se compose de trois parties distinctes :
* Le **modèle** contient les données.
* La **vue** affiche ces données et réceptionne les entrées de l'utilisateur
* Le **contrôleur** organise la mise à jour du modèle et de la vue suite aux entrées de l'utilisateur

L'architecture MVC est notamment utilisée par **Ruby on Rails** pour la mise au point de sites web dynamiques.
<br />

## Les routes

Les routes interprètent les URLs afin d'orienter les requêtes des utilisateurs vers les bonnes actions du contrôleur. Elles doivent être mises en place dans le fichier config/routes.rb pour les sites réalisés avec le framework rails.
Pour plus d'informations vous pouvez consulter le site de la documentation de rails sur les [routes](http://guides.rubyonrails.org/routing.html)
<br />

## Les bases de données

Une base de données est un ensemble de données stockées de façon structurée. Différentes données sont associées entre elles afin de faciliter leur accès ultérieur. Par exemple, un site internet peut stocker les adresses de ses utilisateurs associées à leurs noms. il suffit alors de disposer du nom de l'utilisateur pour accéder rapidement à son adresse.

<br />
## Get/POST

Les méthodes Get et POST sont des **requêtes HTTP**. Elles font parti de la catégorie des requêtes client. Elles viennent du client et sont destinées au serveur. La méthode **Get** est la requête client la plus courante. Elle **ne modifie pas la ressource**. A l'inverse, la méthode **POST modifie la ressource**.
<br />
## Le concept de migration

Les migrations sont une fonctionnalité d'Active Record. Elles facilitent les modifications de la structure et de l'organisation des bases de données. Avec les migrations, les changements dans la structure des données sont indépendants de la base de données elle-même.
Le site de la documentation de rails consacre una article aux [migrations](http://edgeguides.rubyonrails.org/active_record_migrations.html)
<br />
## Les relations entre les modèles et des BDD

Les bases de données stockent l'information d'une façon rationnelle. Il existe plusieurs modèles d'organisation. On peut citer le modèle de base de données hiérarchique, le modèle document ou le schéma en étoile. Les principaux modèles sont listé sur ce [**site**] (https://www.lucidchart.com/pages/fr/quest-ce-quun-mod%C3%A8le-de-base-de-donn%C3%A9es)
Le choix de tel ou tel modèle de base de données dépend d'une multitude de facteurs. On peut citer par exemple le type de données à stocker et la rapidité d'accès à l'information.
<br />
## Les fonctions du CRUD

Le CRUD est un acronyme qui désigne les quatre opérations de base de la gestion de données :
* Create : création de nouvelles données
* Read : lire des données
* Update : modifier des données existantes
* Delete : supprimer des données
