Commande : pwd
Usage : Affiche le chemin absolu du répertoire courant.
Exemple : /home/student

Commande : ls -la
Usage : Liste les fichiers et dossiers avec droits et détails.
Exemple :
-rw-r--r--  1 student student   220 Sep 19 08:00 .bash_logout
drwxr-xr-x  2 student student  4096 Sep 19 08:00 Documents

Commande : cd /etc
Usage : Change de répertoire.
Exemple : /etc

Commande : find / -name passwd 2>/dev/null
Usage : Recherche un fichier par nom.
Exemple : /etc/passwd

Commande : ps aux
Usage : Liste les processus actifs avec détails.
Exemple :
root        1  0.0  0.1 167272  1336 ? Ss   08:00   0:01 /sbin/init
student  1234  0.0  0.2  98032  2340 pts/0 S+  08:05   0:00 bash

Commande : top
Usage : Affiche en temps réel les processus et l’utilisation des ressources.
Exemple :
top - 08:10:01 up  1:23,  1 user,  load average: 0.10, 0.22, 0.08

Commande : kill -9 1234
Usage : Termine un processus par son PID.
Exemple : (le processus 1234 est arrêté)

Commande : whoami
Usage : Affiche l’utilisateur courant.
Exemple : student

Commande : id
Usage : Affiche UID, GID et groupes de l’utilisateur.
Exemple :
uid=1000(student) gid=1000(student) groups=1000(student),27(sudo)

Commande : sudo -l
Usage : Liste les commandes exécutables avec sudo par l’utilisateur.
Exemple :
User student may run the following commands on this host:
    (ALL : ALL) ALL

Commande : chmod 755 script.sh
Usage : Change les permissions d’un fichier.
Exemple : -rwxr-xr-x  1 student student  120 Sep 19 08:00 script.sh

Commande : chown root:root fichier.txt
Usage : Change le propriétaire et le groupe d’un fichier.
Exemple : -rw-r--r--  1 root root  50 Sep 19 08:00 fichier.txt

Commande : ip a
Usage : Affiche les interfaces réseau et leurs adresses.
Exemple :
2: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500
    inet 192.168.1.10/24 brd 192.168.1.255 scope global eth0

Commande : netstat -tulpn
Usage : Affiche les ports ouverts et les processus associés.
Exemple :
tcp   0  0 0.0.0.0:22   0.0.0.0:*   LISTEN   789/sshd

Commande : ping -c 2 8.8.8.8
Usage : Vérifie la connectivité réseau vers une IP.
Exemple :
64 bytes from 8.8.8.8: icmp_seq=1 ttl=115 time=15.6 ms
64 bytes from 8.8.8.8: icmp_seq=2 ttl=115 time=15.4 ms
