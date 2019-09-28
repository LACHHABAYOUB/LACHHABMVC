#MVC

Application web JEE en utilisant les composants Web Servlet, JSP et JSTL. sans faire appel à aucun Framework. 
C'est un exemple d'application web JEE qui respecte le pattern MVC avec une couche métier qui effectue le mapping objet relationnel JDBC. c'est une application qui permet de saisir, ajouter, supprimer, éditer et mettre à jour des produits stockés dans une base de données MYSQL.


l'application se compose de deux couches : 

 *La couche Métier qui contient :
 - Une entité :Produit  
 - Une interface    
 - Un singleton Connection     
 - Une implémentation de l'interface  
 - Une classe pour Tester cette implémentation 
 
 * La couche Web qui contient :   
 - Un modèle    
 - Un contrôleur : Servlet  
 - Une vue JSP     
 - Une feuille de style CSS 
 
 Ca permet d'apprendre les concepts suivants :     
 - Créer une base de données mysql    
 - Effectuer le mapping objet relationnel avec JDBC   
 - Créer un pattern Singleton      
 - Utiliser le pilote JDBC    
 - Respecter le pattern MVC     
 - Créer une servlet    
 - Déployer une servlet :web.xml ou annotations    
 - Créer une JSP en utilisant JSTL  
 - Créer une feuille de style CSS     
 - Ecrire un minimum de javascript
