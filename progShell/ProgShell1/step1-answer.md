Le but de ce premier exercice est de manipuler les mécanismes essentiels du shell

- Créez les fichier suivants 

`touch adresse.txt 'fic$' ficgrep2 notes2.txt adresse2.txt fic.log fichier notes3.txt  agenda.txt fic1 fichier1 out.txt chambresHotes.csv fic2 fichier2 passwd  chifres.txt chifres.php fic866.log hotel.txt readme.txt  dep_56 fic866866.log httpd.conf test dep_89 fic8668661866.log jpawk2 testscript.txt  desktop.ini fic866866866.log jpdata titi exemple fic866868.log linux.txt toto exemple.txt fic867.log liste typescript  expr.txt fic868.log mails.txt users.csv fevrier ficgrep notes.txt ventes.txt  fic ficgrep1 notes1.txt`{{execute}}

1.	Afficher les noms de fichiers se terminant par .php.

`ls *.php`{{execute}}

2.	Afficher les noms de fichiers se terminant par .log.

`ls  *.log`{{execute}}

3.	Afficher les noms de fichiers ayant la lettre ‘i’ en deuxième position.

`ls ?i*`{{execute}}

4.	Afficher les noms de fichiers dont la première lettre est comprise entre b et s.

`ls [b-s]*`{{execute}}

5.	Afficher les noms de fichiers qui ne commencent pas par une voyelle.

`ls [^aeuioy]*`{{execute}}

6.	Afficher les noms de fichiers qui ne se terminent pas par .php.

`ls *.!(log)`{{execute}}

7.	Afficher les noms de fichiers qui ne se terminent ni par .txt ni par .php.

`ls *.!(log|txt)`{{execute}}

8.	Afficher tous les fichiers qui contiennent la chaine « 866 » au moins une fois.

`ls *@(866)*`{{execute}}

9.	Afficher tous les fichiers qui contiennent ou pas la chaine "abc"

`ls *?(abc)*`{{execute}}

10.	Afficher tous les fichiers qui contiennent une ou plusieurs fois les chaines "abc" ou "866"

`ls *+(abc|866)*`{{execute}}