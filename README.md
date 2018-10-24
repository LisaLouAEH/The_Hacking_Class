## The hacking class ##
<hr/>

> Tu vas encore faire un site d'éducation en ligne. Dans ce site il y aura des élèves qui peuvent s'inscrire à un seul cours. Un cours pourra avoir plusieurs élèves.   

<hr/>

## De la reflection sur l'architecture aux dernières erreurs rencontrées:  

* 3 tableaux répartis comme suis/  

L tab **student** :   
----L champs :  
--------L id (integer primary key autoincrement)  
--------L name (string)   
  
L tab **courses**:  
----L champs :  
--------L id (integer primary key autoincrement)  
--------L user_id (belongs_to user: index)   
--------L pin_url (string)   

  
* Un étudiant est inscrit à un seul cours 
* Un cours est suivi par plusieurs étudiants