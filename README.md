# Explication des concepts fondamentaux de rails

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
<br />
Site statique : Page web dont le contenu est généré antérieurement à sa consultation.
Site dynamique : Page web dont le contenu est généré postérieurement à la requête de consultation.
