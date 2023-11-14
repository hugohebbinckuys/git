

-> git --version = version et verif que bien installé 
-> git init  = Premiere commande a taper sur chaque projet si on veut l'initialiser en tant que depot git  => et enft ca crée un dossier caché .git (qu'on peut voir si on fait ls -a (et pas ls tout simple))
-> git add = tracker des fichiers 
-> git add -A = track tous les fichiers existants 
-> git commit -m "initialisation [par exemple]" capture l'etat d'un projet à un point dans le temps
-> git remote
-> git push 
 

-> dans un fichier (avec vim) pour quitter et sauvegarder faire echap puis ':wq' 

-> rm -rf .git => supprimer le depot git local initialisé 

-> git pull = quand on a un fichier qui a ete update sur github par qq d'autre par exemple et bah si on veut push un travail on peut pas avant d'avoir pull c a d récup le travail et l'update de l'autre. 
donc git pull origin master par exemple si c le chemin origin de la branche master puis git push origin master 

git ignore => fichier/dossier qu'on veut pas prendre dans le depot. 