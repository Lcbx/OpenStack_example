Openstack id/pw INF8480-33 : X5Nym9Hhh



Dans src :


Pour simple_server :
faire : source ./INF8480-33-projet-openrc.sh     et entrer le mdp
lancer le gabarit heat correspondant via Openstack s'il ne roule pas deja
puis faire : nova add-floating-ip server 132.207.12.93
et voila ca marche (ouvrez votre browser sur 132.207.12.93:8000 pour un test rapide)


Pour Complex :
lancer le gabarit heat correspondant via Openstack s'il ne roule pas deja
c'est tout :p


rouler benchmark.sh apres chacun des manipulations plus tot
ne pas oublier de faire avant chmod u+x ./benchmark.sh
NOTE: wget stocke le contenu de la page, d'ou l'option -q0

nos resultats (30 requetes)
simple_server: 32.034s
Complex : 12.045s
serveur local : 38.135s

