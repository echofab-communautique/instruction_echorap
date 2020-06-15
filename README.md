# ÉchoRap

>Créateur=Stéphane Rousseau, ADI, Échofab
Description projet=Imprimante 3D basée sur le projet RepRap.
Outil utilisé=Outils d'électronique
Status=Terminé
License=GPL
Image principale projet=EchoRapMainSmall.jpg
Image projet=Echorapv3-1.jpg, Echorapv3-3.jpg, Echorapv3-2.jpg, Echorapv3-4.jpg
Taille image=Grande
Usage=Tiré du site web de Robotic Sequencing

- Dès sa sortie de l’emballage, l’ÉchoRap vous permet d’imprimer des pièces totalement fonctionnelles en acrylonitrile butadiène styrène (ABS) et en nylon et de réaliser de superbes designs en acide polylactique (PLA).//
- L’ÉchoRap possède un énorme volume d’impression de 6784 centimètres cubiques (414 pouces cubes) et une résolution de couche d’impression de 100 microns.// 
- Elle a été développée avec des logiciels et du matériel en code source ouvert pour vous permettre de continuer à l’optimiser en y intégrant les futures avancées technologiques en matière d’impression 3D.//
- Elle est facile à assembler et à entretenir et est construite avec des pièces qui ont fait leurs preuves afin de vous garantir une grande fiabilité.//
- Son design sous licence Creative Commons Non-Commercial vous permet d’imprimer des pièces de l’imprimante et même d’en assembler une pour l’offrir en cadeau!//




## Étapes pour l'impression 3D

1- Modélisation (//[[http://www.sketchup.com/intl/fr/download/gsu.html|Sketchup]]//)

2- Exporter en fichier STL à l'aide du plugin //[[http://sourceforge.net/projects/stl4su/|"Sketchup to STL"]]// ([[Installation du plugin Sketchup-to-STL]])

3- Centrer et positionner le modèle dans "l'espace 3D" à l'aide de //[[http://replicat.org/download|ReplicatorG]]//

4- Envoyer le fichier STL pour qu'il soit corrigé vers le "cloud" de //[[http://cloud.netfabb.com/|netFabb]]//

5- Découper en couches à l'aide de //[[http://slic3r.org/|Slic3r]]// avec les paramètres de l'imprimante 3D. (config. à venir)

(suite bientôt!!)

## Comment changer le filament

Afin de changer le filament de PLA ou d'ABS il faut tout d'abord s'assurer que la température de l'extrudeuse soit assez élevée pour que le plastique soit liquide. Dans la console d'impression de Cura on peut entré manuellement la température 190C pour le PLA ou 220 pour l'ABS et confirmé en appuyant sur la touche "Entrée". La température devrait commencer a monter sur le graphique.



![EchorapF1](https://user-images.githubusercontent.com/65183668/84680259-ad5cff00-af32-11ea-9858-9f2642f83f99.jpg)



Une fois la température atteinte, on s'assure que les moteurs ne soient pas sous tensions. En envoyant la commande "M84" (avec un "M" majuscule) dans l'onglet "Term" de la console d'impression, l'imprimante devrait couper l'alimentation des moteurs permettant ainsi de bouger manuellement les axes et faire tourner sans trop de force l'engrenage de l'extrudeuse.



![EchorapF2](https://user-images.githubusercontent.com/65183668/84680265-ae8e2c00-af32-11ea-8e60-b755e6ea2e99.jpg)



En tournant manuellement la roue dentée de l'extrudeuse dans le sens antihoraire, le filament devrait commencer a être entraîné lentement vers le haut. Après quelques tours, il ne devrait plus être coincé dans le mécanisme et on devrait pouvoir le retirer sans problème. 



![EchorapF3](https://user-images.githubusercontent.com/65183668/84680269-afbf5900-af32-11ea-8f0a-e9723c9a9db0.jpg)



Pour insérer un filament dans l'extrudeuse, c'est l'inverse. On insère le bout du filament dans l'entrée de l'extrudeuse et en appliquant une assez bonne pression sur le fil. On tourne manuellement la roue dentée dans le sens horaire. La pression qui devra être appliquée sur le fil dépendra de la force appliquer par les ressorts sur le côté de la tête.



![EchorapF4](https://user-images.githubusercontent.com/65183668/84680272-b057ef80-af32-11ea-9089-98052326bfd4.jpg)



Après quelques tours, le nouveau filament devrait commencer à sortir de la tête!



![EchorapF6](https://user-images.githubusercontent.com/65183668/84680278-b221b300-af32-11ea-959a-6e34bf417738.jpg)


## échoRap v0.9
ÉchoFab possède une échoRap v0.9 que nous utilisons encore avec de très bon résultat.

#### Spécification
**Surface d'impression** : 20cm x 20cm x 20cm

**Matériaux utilisable** : PLA / ABS

**Plaque chauffante** : Oui

**Controllée avec** : Cura

#### Détails technique
Steps per Unit (Configuration du firmware Marlin / Gen7 Electronics )

X 44.4444 / Y 44.4444 / Z 2267.717 / E 400

Steps per Unit (Configuration du firmware Sprinter / Printerboard )

X 44.4444 / Y 44.4444 / Z 2267.717 / E 375


## Documentation
Description de l'EchoRap en anglais sur le site du concepteur Robotique Sequencing: [[http://www.roboticsequencing.com/products-2/echorap/]]

Entrée sur RepRap: [[http://www.reprap.org/wiki/Echorap]]

Fichier STL pour imprimer les pièces de votre propre échoRap: [[http://www.thingiverse.com/thing:32557 EchoRap sur Thingiverse]]

Téléchargement du firmware dans l'échoRap (instruction en anglais): 

Pour les échoRap utilisant la carte électronique PrintrBoard Rev D:
[[https://github.com/roboticseq/RSEchoRapSprinterForPrintrBoardRevD/blob/master/README]]

Pour les échoRap utilisant la carte électronique Gen7 1.3.1:
[[https://github.com/roboticseq/RSEchoRapMarlinForGen7v131]]
