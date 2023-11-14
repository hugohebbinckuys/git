user@user-Latitude-3420:~/Documents/Cours/L2/Gestion de projet$ git add -A
error: 'git/' n'a pas de commit extrait
fatal: échec de l'ajout de fichiers
user@user-Latitude-3420:~/Documents/Cours/L2/Gestion de projet$ ls
'apprentissage du mkdown.pdf'   MontProjetGit         'question gestion projet cours1.docx'
 clone                          obsidian              'question gestion projet cours1.odt'
 git                            projetMethodesAgiles
user@user-Latitude-3420:~/Documents/Cours/L2/Gestion de projet$ cd git
user@user-Latitude-3420:~/Documents/Cours/L2/Gestion de projet/git$ ls
git  Mon_projet  projetDossier1  projetTest  projetTEST2
user@user-Latitude-3420:~/Documents/Cours/L2/Gestion de projet/git$ cd git
user@user-Latitude-3420:~/Documents/Cours/L2/Gestion de projet/git/git$ ls
'Clé ssh pour push et pull avec depot distant.md'   img.md
 commandes_imp.md                                  'important sur git.md'
 commandes.md                                      'infos importantes un peu bordel.md'
'cours sur git.md'                                 'presentation Lean Softare Development.md'
'Git clone.md'                                     'projet methode agile'
 home
user@user-Latitude-3420:~/Documents/Cours/L2/Gestion de projet/git/git$ git init
Dépôt Git existant réinitialisé dans /home/user/Documents/Cours/L2/Gestion de projet/git/git/.git/
user@user-Latitude-3420:~/Documents/Cours/L2/Gestion de projet/git/git$ git add -A
warning: dépôt git embarqué ajouté : projet methode agile
astuce: You've added another git repository inside your current repository.
astuce: Clones of the outer repository will not contain the contents of
astuce: the embedded repository and will not know how to obtain it.
astuce: If you meant to add a submodule, use:
astuce: 
astuce: 	git submodule add <url> projet methode agile
astuce: 
astuce: If you added this path by mistake, you can remove it from the
astuce: index with:
astuce: 
astuce: 	git rm --cached projet methode agile
astuce: 
astuce: See "git help submodule" for more information.
user@user-Latitude-3420:~/Documents/Cours/L2/Gestion de projet/git/git$ git status
Sur la branche master
Modifications qui seront validées :
  (utilisez "git restore --staged <fichier>..." pour désindexer)
	modifié :         .obsidian/app.json
	nouveau fichier : .obsidian/graph.json
	modifié :         .obsidian/workspace.json
	modifié :         commandes.md
	nouveau fichier : commandes_imp.md
	nouveau fichier : cours sur git.md
	supprimé :        depot git local dans depot git distant.md
	nouveau fichier : home/user/Images/photo-1575936123452-b67c3203c357.avif.md
	nouveau fichier : img.md
	modifié :         infos importantes un peu bordel.md
	nouveau fichier : presentation Lean Softare Development.md
	nouveau fichier : projet methode agile

user@user-Latitude-3420:~/Documents/Cours/L2/Gestion de projet/git/git$ git commit -m"fichiers pour projet web"
[master bb26acf] fichiers pour projet web
 12 files changed, 198 insertions(+), 59 deletions(-)
 create mode 100644 .obsidian/graph.json
 create mode 100644 commandes_imp.md
 create mode 100644 cours sur git.md
 delete mode 100644 depot git local dans depot git distant.md
 create mode 100644 home/user/Images/photo-1575936123452-b67c3203c357.avif.md
 create mode 100644 img.md
 create mode 100644 presentation Lean Softare Development.md
 create mode 160000 projet methode agile
user@user-Latitude-3420:~/Documents/Cours/L2/Gestion de projet/git/git$ git remote add web git@github.com:hugohebbinckuys/projetWebfctv.git
user@user-Latitude-3420:~/Documents/Cours/L2/Gestion de projet/git/git$ git push -u web master
Énumération des objets: 29, fait.
Décompte des objets: 100% (29/29), fait.
Compression par delta en utilisant jusqu'à 8 fils d'exécution
Compression des objets: 100% (24/24), fait.
Écriture des objets: 100% (29/29), 9.78 Kio | 1.63 Mio/s, fait.
Total 29 (delta 5), réutilisés 0 (delta 0), réutilisés du pack 0
remote: Resolving deltas: 100% (5/5), done.
To github.com:hugohebbinckuys/projetWebfctv.git
 * [new branch]      master -> master
La branche 'master' est paramétrée pour suivre la branche distante 'master' depuis 'web'.
user@user-Latitude-3420:~/Documents/Cours/L2/Gestion de projet/git/git$ 
:wq

