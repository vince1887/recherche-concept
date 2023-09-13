# Laser
Les projecteurs de laser servent a projeter des faisceaux lasers colorés à travers un système optique complexe, contrôlés par des logiciels. Les laser émettent de la lumière qui est ensuite dirigées a l'aide de mirroirs et de lentilles.

### Contexte d'utilisation
- spectacles et concerts
- boîte de nuit
- Instalations

![image du boitier de laser](/images/laser_boitier.JPG)
### Module d'emission de lasers
![image interieur laser](/images/laser_interieur.JPG)
### Module de déplacement des lasers
![image daplacement des lasers](/images/laser_deplacement.JPG)

## Contrôle des lasers (protocol)

### ilda (analogue)



### dmx (numérique)

Très limité comme méthode de contrôle, par contre limite la quantité de programation a faire.
Permet de faire jouer des patterns prédéfinie

### fb4 (numérique + standalone)

Le FB4 Ilda est est un "network hardware" produit par Pangolin. Il permet la même latitude de contrôle que le Ilda, mias avec un network setup (ArtNet).

Le FB4 Ilda est aussi équipé d'un entré pour carte SD qui lui permet de jouer par lui même en mode "repeat". 

source: https://phantomdynamics.com/pangolin-fb4-ilda-w-quickshow/

## Exemple dans le contexte d'un concert
[![Thumbnail video concert laser](https://img.youtube.com/vi/QtXx3Qubmys/0.jpg)](https://www.youtube.com/watch?v=QtXx3Qubmys&t=1833s)

## Exemple dans le contexte d'une instalation
[![Thumbnail video laser intearctif](https://img.youtube.com/vi/tRIWF3Hhrew/0.jpg)](https://www.youtube.com/watch?v=tRIWF3Hhrew)
[![Thumbnail video laser intearctif](https://img.youtube.com/vi/l2j3lmJM_zw/0.jpg)](https://www.youtube.com/watch?v=l2j3lmJM_zw)

## Moment Factory Lab 
En déambulant sur la page de Moment Factory Lab j'ai trouver un example d'interactivité 
- https://momentfactory.com/labo/laser-interactif (interactive Physique + laser)
- https://momentfactory.com/labo/gesture-controlled-sharpies (controler des lumières avec par détection de corps)
- https://momentfactory.com/labo/sculpter-lespace-en-lumiere (laser vers les gens?)
# Osciloscope Music
 L'osciloscope music est une musique qui génère son propre visuel. Le visuel se génère en séparant le canal de gauche et de droite pour les asigner à des valeurs en X et Y. Le but est donc de créer quelque chose de plaisant à regarder et écouter. Donc le "visuel" est eimpreigner en qulque sorte dans le fichier audio.
 
 Pour créer ce genre d'oeuvre on peut utiliser des fonctions mathématique pour créé la forme d'onde sonore et ensuite la dessiner sur l'osciloscope. La deuxième méthode est de créer des formes/models 3D et les convertire en onde sonore avec le logiciel OsciStudio.

(2:09 +  6:00 + 15:00)

[![Thumbnail video osciloscope musique](https://img.youtube.com/vi/4gibcRfp4zA&t/0.jpg)](https://www.youtube.com/watch?v=4gibcRfp4zA&t)
 

## Logiciel utilisé
  https://oscilloscopemusic.com/software/oscistudio/

### exemple d'osciloscope music avec des fonctions mathématique
[![Thumbnail video osciloscope musique](https://img.youtube.com/vi/Nt1PXQ2ah3A&t/0.jpg)](https://www.youtube.com/watch?v=Nt1PXQ2ah3A&t=1s)


# Micro contact (piezo)

C'est simplement un type de micro qui capte les vibrations matériels (contact physique), contrairement à un micro "conventionel" qui capte les variations de la pression de l'air.

L'appélation plus technique microphone piezoélectrique provient du fait que la membrane subi une déformation méchanique pour créer le courant électrique. (piezoélectricité)

![image reference piezo microphone](/images/piezo_example.jpg)

## Différence avec un Micro "conventionel"
- moin couteux qu'un microphone de studio
- Plus petit, donc facile à intègrer
- Il n'ont pas de direction
  
### Feedback
Dans le contexte d'un instalation interactive qui produit du son et qui utilise un microphone, l'utilisation de microphone plus "conventionel" pourrait entrainer du feedback. Par contre, le micro contact ne devrait pas.
 
## Example 
[![Thumbnail video noise box](https://img.youtube.com/vi/AN38SbrbizQ/0.jpg)](https://www.youtube.com/watch?v=AN38SbrbizQ)


# image to sound
transforme les image en sound 
https://nsspot.herokuapp.com/imagetoaudio/
