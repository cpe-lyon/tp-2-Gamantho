# Compte Rendu TP 2

## Exercice 1 Variable d'environnement

**Question 1**
Ils trouvent les commandes tapés par l'utilisateur dans la variable bash.
/usr/local/bin

**Question 2**
C'est la variable d'environnement HOME qui permet a la commande cd de nous ramener dans le répertoire personnel.

**Question 3**
La variable LANG permet de connaitre la langue utilisé par le système : On peut le voir avec 
-printenv LANG : en_US.UTF-8
La variable PWD permet de voir le chemin courant: -echo "$ PWD"
La variable OLDPWD permet de voir l'ancien chemin courant -echo "$OLDPWD"
La variable SHELL contient l'interpréteur de commande de l'utilisateur tel qu'il est défini dans le fichier /etc/passwd.

**Question 4**
On créer la variable a l'aide de la commande -MY_VAR="123456", on peut afficher le contenu de la variable avec -echo $MY_VAR.

**Question 5**
La commande bash lance une nouvelle session locale sur la machine, la commande echo my_var ne trouve pas de correspondance car la variable a été déclaré en local. En rentrant la commande -exit on peut accéder de nouveau a la variable MY_VAR.

**Question 6**
Pour la transformation en variable d'environnement on utilise: -export MY_VAR="123456"
printenv MY_VAR.

**Question 7**
On créer la variable d'environnement souhaité avec la commande -
export NOM="Gamard Anthony" on regarde si la valeur est correct avec echo $NOM

**Question 8**
 On utilise la commande  echo 'Bonjour à vous, ' $NOM

**Question 9**
 La commande -unset va supprimer la variable d'environnement alors que donner une valeur vide laissera juste un contenu vide.
 
**Question 10** 

La commande -echo 'HOME' = "$HOME" nous permet d'afficher le chemin de notre dossier personnel.

## Programmation Bash

### Exercice 2 Contrôle de mot de passe 
voir sur le word fournis a coté 

### Exercice 3 Expressions rationnelles
voir sur le word fournis a coté 

### Exercice 4 Contrôle d'utilisateur
voir sur le word fournis a coté 

### Exercice 5 Factorielle


### Exercice 6 Le juste prix 


### Exercice 7 Statistiques 
 


