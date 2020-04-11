Labo Partie 3 c# Arnaud ZEEVAERT 2226
=====================================

Nom du programme :
------------------
Carnet de musculation

Brève description des classes + les données utilisée :  
-------------
> une classe note
* contient un string pour écrire un commantaire
* contient un int pour exprimer un niveau de difficulté
---
> une classe série
* contient un int pour le nombre de répétitions
* contient un double pour la charge utilisée
* contient le temps de repos
---
> une classe jour
* contient une date
* contient une note
* contient une collection de série
---
> une classe exercice
* contient une image
* contient un nom (string)
* contient éventuellement une description (string)
* contient une collection de jour
---
>  une classe séance
* un nom (string)
* une collection de exercice
---
> une classe entrainement
* un nom (string)
* une collection de séance
---
> une classe personne 
* contient différentes information sur cette personne : nom, prénom, age, sexe, ...
* contient une collection entrainement
---
> une interface pour des méthodes save et load
 
 stockage des données:
 ---------------------
      en XML : les classe personne
      dans la registry : la path des images utilisée
