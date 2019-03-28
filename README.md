# Template pour le Partiel S2H2 à HETIC

Ce projet est un template réunissant les exercisses Routing, methode POST et API du cours de Bruno Simon.


## Construction

Ce projet et concus en suivant la logique du routing 2 du cours. 
Il est donc construit autour d'un index, appellant des "controllers" renvoyant eux même à des "pages" avec un contenu et inclut les "partials" : header et footer.

Ce "routing" est possible grace au lien entre les l'index et les controllers et va permettre, grâce à une méthode GET, d'inscrire une URL correspondant à la page.

Sur la home il y a un petit échange avec une base de donnée avec quelque exemple d'échange.

Sur la page/1 vous trouverez l'exercisse d'API sur la météo. Je ne sais pas si il demandera d'en réalisé une, mais ça peut servir d'exemple. Et le probleme d'une deuxième method GET à été réglée (merci Jules).


## Recommandation d'Utilisation

Pour l'utilisation commencer par installer la base de donnée ou changer les define dans le fichier database. Sinon Vous aurez un certain nombre d'ERROR sur la home.
Deuxième point très important, il faut changer l'URL dans public/index.php. Sinon tout la construction du routing merdera.

Normalement ces deux points sufiront à faire marcher le projet.

Pour dévelloper dessus, il faudra respecter plusieurs points :
  Laissez toutes les logiques php dans les "controlleurs" et ne faites que de la présentation de variable dans les "page".
  Toute la logique JS et CSS se trouvera dans le dossier public/assets/
  Noubliez pas de rajouter les routes dans l'index lorsque vous réalisez de nouvelles pages. Et pensez au "$title".
