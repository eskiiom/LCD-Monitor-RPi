# LCD-Monitor-RPi (Work in progress)
Program to use SPI 20x04 LCD Screen + Push buttons on a Raspberry Pi

## Pré-requis :
- bw_tool [wiki](https://bitwizard.nl/wiki/Bw_tool) Pour l'exploitation de l'écran
- jq [GitHub](https://stedolan.github.io/jq/) Pour l'exploitation des données json de openweathermap
- MPD/MPC Pour la lecture des stream radio ou fichiers mp3 stockés en local
- alsamixer pour la gestion de la sortie audio et du volume de sortie (100% c'est vraiment beaucoup trop)

## Description :
Programmes créés pour utiliser  
les boutons : https://www.bitwizard.nl/wiki/Pushbutton  
l'écran : http://www.bitwizard.nl/wiki/Lcd_protocol_1.6

## Objectif du programme
- Afficher les infos système au démarrage du Pi (date, IP et uptime)
- Bascule sur l'affichage du menu (il est possible de sélectionner l'affichage de la météo, ou des infos système, ou le lecteur radio)
- Sur chaque écran est affiché la date et l'heure, car le but de l'écran est d'etre tout le temps allumé
- Les infos système affichent quelques informations principales
- Le lecteur radio permet de mettre en lecture ou pause, affiche la piste en cours et la durée écoulée/restante. Il permet aussi de gérer le volume.

## How it started
<a data-flickr-embed="true" href="https://www.flickr.com/photos/esquimo_2ooo/7657068098/in/dateposted-public/" title="Rasberry Piiiiiii"><img src="https://live.staticflickr.com/8430/7657068098_0b48696ce5_c.jpg" width="600" height="800" alt="Rasberry Piiiiiii"/></a>
