## The hacking class ##
<hr/>

> Tu vas encore faire un site d'éducation en ligne. Dans ce site il y aura des élèves qui peuvent s'inscrire à un seul cours. Un cours pourra avoir plusieurs élèves.   

<hr/>

## De la reflection sur l'architecture aux dernières erreurs rencontrées:  

* 3 tableaux répartis comme suis/  

L tab **students** :   
----L champs :  
--------L id (integer primary key autoincrement) 
--------L course_id (belongs_to courses: index) 
--------L name (string)   
  
L tab **courses**:  
----L champs :  
--------L id (integer primary key autoincrement)     
--------L title (string)   

  
* Un étudiant est inscrit à un seul cours 
* Un cours est suivi par plusieurs étudiants