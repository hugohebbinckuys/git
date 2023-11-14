
cd
ls
cd Documents/
cd Cours
cd L2
cd Gestion\ de\ projet/
cd git
mkdir projetDossier1
cd projetDossier1/
- git init => initialise le depot git en local 
- vim fichier1.txt => creation d'un fichier lambda dans le depot local 
- git status => pour avoir les infos sur le depot et ses fichiers commit ou non 
- git add fichier1.txt => enregistre l'etat actuel du depot  
- git status 
- git commit -m "initialisation du fichier1 du Dossier1" => on "capture" l'etat du projet [le "initialisation du fichier1 ......." sert à dire les changeùents qu'on a fait au code et l'update qu'on a voulu faire quoi] 
- git remote add origin git@github.com:hugohebbinckuys/dossier1.git => debut de la commande ajoute un nouveau "remote" appelé "origin" au référentiel local. / fin de la commande c'est l'URL du dépôt distant que on va lier au "remote" "origin". Dans cet exemple, il s'agit d'un dépôt sur GitHub, accessible via SSH. Cela signifie que on peut  pousser et tirer des modifications depuis et vers ce dépôt en utilisant la clé SSH associée.
- git push -u origin master => On pousse les modifications locales de la branche "master" vers le dépôt distant 