Voici ce qu'il fait :
Fonctionnement général
Le code utilise un module L298N pour contrôler deux moteurs (gauche et droit) d'un robot. Il reçoit des commandes via la liaison série (Bluetooth) et exécute les mouvements correspondants.
Décomposition du code
Configuration des broches :

Broches 5/6 : contrôle du moteur droit (avant/arrière)
Broches 7/8 : contrôle du moteur gauche (avant/arrière)

Commandes disponibles :

'F' : Avancer - les deux moteurs tournent vers l'avant
'B' : Reculer - les deux moteurs tournent vers l'arrière
'L' : Tourner à gauche - seul le moteur droit tourne (le robot pivote)
'R' : Tourner à droite - seul le moteur gauche tourne (le robot pivote)

Rôle de delay(50)
La ligne delay(50) à la fin sert à :

faire executer chaque commande une durée de 50ms, Ce code Arduino contrôle un robot à deux roues via des commandes Bluetooth

