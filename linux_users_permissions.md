Commande : adduser testuser
Usage : Crée un nouvel utilisateur avec un répertoire personnel.
Exemple :
Adding user `testuser' ...
Creating home directory `/home/testuser' ...
Copying files from `/etc/skel' ...

Commande : passwd testuser
Usage : Change le mot de passe d’un utilisateur.
Exemple :
Enter new UNIX password: 
Retype new UNIX password: 
passwd: password updated successfully

Commande : usermod -aG sudo testuser
Usage : Ajoute un utilisateur à un groupe.
Exemple :
(id testuser → uid=1001(testuser) gid=1001(testuser) groups=1001(testuser),27(sudo))

Commande : groups testuser
Usage : Affiche les groupes d’un utilisateur.
Exemple :
testuser : testuser sudo

Commande : su - testuser
Usage : Permet de basculer vers un autre utilisateur.
Exemple :
$ whoami
testuser

Commande : sudo ls /root
Usage : Exécute une commande avec privilèges administrateur.
Exemple :
[sudo] password for testuser: 
file1.txt  file2.log

Commande : chmod 644 fichier.txt
Usage : Modifie les permissions d’un fichier.
Exemple :
-rw-r--r--  1 testuser testuser  120 Sep 19 10:00 fichier.txt

Commande : chown root:root fichier.txt
Usage : Change le propriétaire et le groupe d’un fichier.
Exemple :
-rw-r--r--  1 root root  120 Sep 19 10:00 fichier.txt
