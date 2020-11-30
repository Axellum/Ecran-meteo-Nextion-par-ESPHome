# Ecran météo Nextion par ESPHome
Ecran météo pour Home Assistant: Utilisation de ESPHome, Météo France + commandes interrupteurs.

![](/20201123_122256.jpg)

Version simplifié. En cour de construction.

Au menu:
- Date et horloge.
- Temps actuel.
- Détecteur gel, neige et un capteur de présence (portable).
- Retour d'infos de températures et hydrométrie de ses propre sondes.
- Prévision sur trois jours (+ du jour en cour), avec températures mini/maxi.
- 4 boutons pour gérer des intérupteurs, avec retour sur l'etat.
- Luminositée de l'écran réglable sur les icones "Journée" et "3 jours".
- Apel de scripts pour changer de couleur sur une ampoule RGB sur les icones "Demain" et "2 jours".
- Couleurs des températures des sondes en fonction de la valeur géré par l'ecran.
- Changement de couleur de texte et de l'icone de vigilence par l'ecran, via un champ cacher.

Vous trouverez sur ce git:
- Le fichier GIMP afin de pouvoir modifier l'esthétique, adapter les icones ex.
- Le fichier HMI pour l'écran Nextion.
- Le fichier yaml pour l'esp32, à adapter en fonction de ses capteurs / interrupteur.
- Le fichier configuration.yaml de Home assistant, à adapter aussi avec son integration Météo France et ses capteurs.
- Le fichier script que j'utilise pour mes commandes, en guise d'exemples.

Les icônes viennent de https://icon-icons.com/fr/pack/The-Weather-is-Nice-Today/1370, création de Laura Reen. J'ai parfois apporté de légère modifications.
