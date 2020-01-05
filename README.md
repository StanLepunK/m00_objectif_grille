# Code créatif Module 00 grille

## version
v 0.1.0

## objectif
Réaliser à l'aide du langage Processing les exercices suivants.
Un exercice est soit raté, soit réussit, sauf indication contraire.
Chaque exercice rapporte des points, pour valider un module il faut obternir au moins 60% des points de l'ensemble du modules.
Dés que la norme n'est pas respectée, l'exercice est considéré comme raté.

L'ensemble des exercices sont à renvoyer par mail au correcteur en respectant l'arborescence et le nommage des dossiers, sous-dossiers et nom de fichiers. Si l'arborescence n'est pas respectée l'exercice ou le module ne seront pas corrigés et considérés comme ratés.

Vous avez des listes de `primitive, globale, opérateur, méthode, condition` ou `itération` que vous pourrez utiliser. Il n'est pas obligatoire de toutes les utiliser, par contre vous ne pouvez pas en utiliser d'autres.

La taille de la fenêtre pourra être changée par le correcteur.

```
dossier : nom prénom
sous-dossier : m##
sous-dossier : m##_ex##_nom
fichier :  m##_ex##_nom.pde
```

* exemple `Maurice_Dupont/m00/m00_ex_00_truc/m00_ex_00_truc.pde`


contraintes : 
respecter la [norme](https://github.com/StanLepunK/La-Voie-du-Code/blob/master/norme_voie_du_code.md)


## ex00_window
```
sketch : ex00_window.pde
xp : 5 / 70
intitulé :
Créer une fenêtre de 640 par 480.
```
```
primitive : 
globale : 
operateur : 
methode primaire : setup()
methode secondaire : size()
condition :
itération :
```
## ex01_background
```
sketch : ex01_background.pde
xp : 10 / 70
intitulé :
Créer une fenêtre de 640 par 480 et définir la couleur de la fenêtre.
```
```
primitive : 
globale : 
opérateur : 
méthode primaire : setup()
méthode secondaire : size(), background()
condition :
itération :
```
## ex02_rectangle
```
sketch : ex02_rectangle.pde
xp : 15 / 70
intitulé :
Créer une fenêtre de 640 par 480 et définir une couleur d'arrière-plan.
Afficher un rectangle dans la partie droite, celui-ci fera la moitié de la fenêtre et devra être d'une couleur différente de l'arrière plan.
```
```
primitive : 
globale : width, height
opérateur : /
méthode primaire : setup()
méthode secondaire : size(), background(), fill(), rect()
condition :
itération :
```

## ex03_diptyque
```
sketch : ex03_diptyque.pde
xp : 25 / 70
intitulé :
Créer une fenêtre de 640 par 480.
Afficher deux rectangles l'un dans la partie droite, l'autre dans la partie gauche ; leur surface hors contour devront être égales, leur contour passera par la ligne médiane et verticale de la fenêtre.
Le contour des deux rectangles sera d'une troisième couleur et de 10 pixels d'épaisseur.
Attention Le contour devra être de la même épaisseur sur l'ensemble de la fenêtre.
```
```
primitive : 
globale : width, height
opérateur : / -
méthode primaire : setup()
méthode secondaire : size(), background(), fill(), stroke(), strokeWeight(), rect()
condition :
itération :
```
## ex04_bande
```
sketch : ex04_bande.pde
xp : 35 / 70
intitulé :
Dans une fenêtre de 640 par 480,
Afficher 10 bandes horizontales d'une même épaisseur et sans contour.
Les bandes devront avoir une longueur égale à la fenêtre et être réparties sur toute la hauteur.
Elles seront de deux couleurs différentes qui devront alterner.
L'emploi du modulo est un plus.
```
```
primitive : int
globale : width, height
opérateur : = / < % * + == ++ +=
méthodes primaire : setup()
méthodes secondaire : size(), noStroke(), fill(), rect(), line()
condition : if
itération : while()
```
## ex05_grille
```
sketch : ex05_grille.pde
xp : 50 / 70
intitulé :
Dans une fenêtre de 640 par 480.
La fenêtre devra afficher 100 cases espacées de façon égales.
L'emploi d'une double boucle un plus.
```
```
primitive : int
globale : width, height
opérateur : = / < * ++ += +
méthode primaire : setup()
méthode secondaire : size(), background(), rect(), line(), fill(), stroke(), strokeWeight() 
condition :
itération : while()
```

## ex06_damier
```
sketch : ex06_damier.pde
xp : 70 / 70
intitulé :
Dans une fenêtre de 480 par 480.
La fenêtre devra afficher un damier régulier en noir et blanc de 10 sur 10;
```
```
primitive : int
globale : width, height
opérateur : = / < * ++ += + % ==
méthode primaire : setup()
méthode secondaire : size(), background(), rect(), line(), fill(), stroke(), strokeWeight()
condition : if, else
itération : while()
```
