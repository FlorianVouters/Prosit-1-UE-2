Prosit 1 UE 2 � Int�gration et maintenance d&#39;un serveur

**Mots Cl�s**

- GLD
- Windows Server
- Linux
- Intranet
- Serveur Sans OS
- Debian
- SI
- Analyser de performances
- Proc�dures d&#39;installation
- Plan pour ce cas de figure
- Panne
- Signalement

**Besoins**

-  Quoi :** Panne de serveur, plan de sauvegarde (plan de reprise d&#39;activit�s).
-  Comment :** Installation server + Ecrire un plan + Surveiller perf + param�trer le serveur.
-  Porqu� :** Pour rendre l&#39;infrastructure fonctionnelle et pr�voir d&#39;autre probl�mes.

**Contraintes**

- Utilisation de Linux (Debian 8.6)

**Probl�matique**

- Comment cr�er un plan permettant de g�rer les pannes ?
- Comment installer un serveur Linux ?

 Bref,

- Comment rendre une infra fonctionnelle et �viter les pannes en �tablissant un plan ?

**G�n�ralisation**

- MCO (Maintient en Conditions Op�rationnels)

**Hypoth�ses**

- Il existe un monitor de perf sur linux qui s&#39;appel : System Monitor.
- On doit config l&#39;interface r�seau.
- On doit (bien) nommer la machine.
- On doit t�l�charger des paquets.
- Connection a un DHCP.
- Faire plusieurs types de serveurs � tempo diff.
- Utiliser Apacheu 2.
- Disques en RAID
- Affecter un DNS
- Cr�er une image � Master �.
- Configurer les droits de plusieurs utilisateurs.
- Configurer un acc�s distant.

**Plan d&#39;action**

Etudes

- Installation d&#39;un serveur (Qu&#39;est-ce qu&#39;on va mettre dessus ? Dimensionnement)
- Param�trer un serveur (Infrastructure r�seau, utilisateurs, acc�s distants, fr�quences des MAJs, pare-feu, dimensionnement du serveur)
- Plan de reprise d&#39;activit�s
- Sauvegardes (quoi, ou, comment, quand �)
- Raid
- Solution de monitoring

R�alisations

- Installation LinuxSS
- Ecrire un plan d&#39;installation
- Param�trer le serveur
- Plan de reprise d&#39;action
- Installer solution de monitoring