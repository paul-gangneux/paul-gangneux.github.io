## Little C program

Projet personnel fait en C avec la librairie SDL. Ce programme est une série de mini-jeux, et me permet de me faire la main sur les techniques qui aboutissent à un moteur 2D optimisé et multi-plateforme.
Il contient pour le moment un Jeu de la Vie (Conway's game of life), et une petite simulation de vaisseau spacial.

[code source](https://github.com/paul-gangneux/little-c-program)

<iframe width="720" height="480" src="vids/gameoflife.mp4" frameborder="0"> </iframe>

<iframe width="720" height="480" src="vids/space.mp4" frameborder="0"> </iframe>


## Ghostlab

Projet scolaire de 3eme année de licence, ghostlab est un petit jeu multijoueur en ligne avec un serveur codé en C et un client codé en Java. Le but de ce projet était de créer des programmes qui manipulent directement les protocoles réseaux (TCP, UDP, Multicast), avec multi-threading (bonne gestion des mutexes et variables partagées), resistant aux erreurs (pas de bug ou fuite de mémoire en cas de déconnexion imprévue), et pouvant communiquer ensemble, ou avec tout autre programme respectant le protocole.
Le projet a été fait en groupe. Je me suis personnellement occupé de coder tout le serveur, de gérer en partie la structure globale du projet (dont les scripts de compilation), et ai aidé pour coder la partie communication réseau du client.

[code source](https://github.com/paul-gangneux/ghostlab)

<iframe width="900" height="480" src="pics/ghostlab2.png" frameborder="0"> </iframe>

<iframe width="720" height="432" src="pics/ghostlab1.png" frameborder="0"> </iframe>