
regarder la video si compliqué : https://codeur-pro.fr/acceder-en-ssh-a-vos-depots-git-distants-github/

-> d'abord générer une paire de clés ssh sur la machine via le terminal 
Par defaut la clé est sauvegarder dans le repertoire : <b> /home/user/.ssh/id_rsa </b> 
On ne va pas changer ca.
(C'est dans un dossier caché (on le voit car c dans /user/.ssh/) or dossier/fichier qui commence par . est caché)

-> Ensuite il demande d'entrer un mdp en plus si on veut (meme sans ce sera sécurisé) 
-> si pas de mdp sécurisé quand meme mais juste pas besoin de ressaisir le mdp a chaque push/pull 
-> La clé est généré. Pour retoruver les fichiers générés on va dans le repertoire .ssh (caché) (-> /home/user/.ssh/ ) puis on ouvre le fichier id_rsa.pub (ATTENTION important de prendre id_rsa.pub et non id_rsa car c la privée cell la) et on voit toute la clé la.

-> puis copier le contenu et aller sur github 
-> dans github aller dans settings / ssh et GPG keys 
-> ajouter une clé ssh 
-> 