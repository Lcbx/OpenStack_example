Openstack:
Username: INF8480-33
Password: X5Nym9Hhh



Code dans le dossier src.


Pour simple_server :
Faire : source ./INF8480-33-projet-openrc.sh     et entrer le password
Lancer le gabarit heat correspondant via Openstack s'il ne roule pas d�j�
puis faire : nova add-floating-ip server 132.207.12.93
et voila �a marche (ouvrez votre browser sur 132.207.12.93:8000 pour un test rapide)


Pour Complex :
Lancer le gabarit heat correspondant via Openstack s'il ne roule pas d�j�, c'est tout!


Rouler benchmark.sh apr�s chacune des manipulations plus t�t
Ne pas oublier de faire avant: chmod u+x ./benchmark.sh
NOTE: wget stocke le contenu de la page, d'ou l'option -q0

Nos r�sultats (30 requ�tes):
simple_server: 32.034s
Complex : 19.936s

