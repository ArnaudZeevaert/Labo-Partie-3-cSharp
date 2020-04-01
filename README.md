Labo Partie 3 c# Arnaud ZEEVAERT 2226

Carnet de musculation

Les données :  
  une classe note
        --> contient un string pour écrire un commantaire
        --> contient un int pour exprimer un niveau de difficulté
  une classe exerciceBase
        --> contient une image
        --> contient un nom (string)
        --> contient éventuellement une description (string)
  une classe série
        --> hérite de la classe séance
        --> contient en plus un int pour le nombre de répétitions
        --> contient en plus un double pour la charge utilisée
        --> contient en plus le temps de repos
  une classe exercice 
        --> qui hérite de exerciceBase
        --> qui contient en plus : une collection de série, et un objet note  
  une classe séance
        --> un nom (string)
        --> une collection de exercice
  une classe entrainement
        --> un nom (string)
        --> une collection de séance
  une classe personne 
        --> contient différentes information sur cette personne : nom, prénom, age, sexe, ...
        --> contient une collection entrainement
 
 stockage des données:
      en XML : les classe personne
      dans la registry
