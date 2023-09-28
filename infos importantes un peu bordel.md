
## init d'un depot git 


on a fait la : 
- mkdir mon_Projet 
- cd Mon_projet 
- vim README.md // fichier pour documenter le projet 
- git init
	--> git init initialise un dépot git dans le repertoire courant
		Un depot git est un systeme de gestion de versions qui permet de suivre et gerer les modifs de notre code etc. une fois qu'un depot git est initialisé il commence à enregistrer les modif qu'on apportera aux fichiers du projet 
			<b> Il faut absolument ajouter un fichier au depot git sinon Git n suit pas les repertoires vides ! (ou alors ajouter un fichier .gitkeep pour un repertoire qu'on veut inclure mais qui n'a pas encore de fichier) </b> 
		
	depot = "projet" en gros 


Git init = Premiere commande a taper sur chaque projet si on veut l'initialiser en tant que depot git  => et enft ca crée un dossier caché .git (qu'on peut voir si on fait ls -a (et pas ls tout simple))

ensuite git status permet de voir la situation actuelle de notre depot 
on voit que pour l'instant avec ces deux commandes y a juste eu deux fichiers mais qui ne sont pas trackés 

-> si on veut le faire on doit faire git add [et les fiochiers qu'on veut tracker] 
si on modifie un fichier et qu'on refait git status on voit que le fichier a ete modifié, il traque nos fichier 
=> si on refait un git add il va sauvegrader etc. 
ensuite on va garder en le statut actuel et en faire un backup -> ouvre un nano pour ecrire ce quo'n a fait du genre 'jai modifié cette partie la ou quoi'; 

faut donc faire git commit -m "initialisation [par exemple]"
git commit capture l'etat d'un projet à un point dans le temps

ensuite faire un git remote add origin [jsp trop prq] /url du depot distant/ 
La je crois que du coup il est connecté avec le depot distant 

puis faire un git push -u origin main [ou master] 
/!\ --> pour le git push et l'authentification, Github a desactove depuis AOut 2021 l'authentifcation par mdp github, il faut générer une cl2 qu iremplacera le mdp 
/!\ !! ATTENTION -> les cles générés ne peuvent plus etre vues donc la noter et tout ! 

on doit ensuite faire un git push mais ca revoir la video car jsp bien

git log permet de voir tous les commit qu'on a eu a faire 

Pour l'instant on a initialisé un depot git et tout et ajouté des fichiers tout ca mais rien de bien ouf 
