# OpenDwarfFortress_v0.2
Refonte du projet ODF avec pyglet (au lieu de pygame).
L'objectif est de creer clone du jeu Dwarf Fortress en Open Source en améliorant l'interface et en ajoutant des fonctionnalitées tout en conservant la profondeur de jeu. Vous pouvez voir un exemple de monde generé dans le dossier Capture.

Pour comprendre le code rendez vous sur le wiki : http://gnu-bricoleur.tuxfamily.org/dokuwiki/doku.php?id=start

Et pour suivre l'avancement du projet, passez sur mon blog : http://gnu-bricoleur.tuxfamily.org/

Pour installer ODF, 4 petites étapes :
Ouvrez une console dans le dossier ou vous souhaitez installer ODF et tapez :

git clone https://github.com/Gnu-Bricoleur/OpenDwarfFortress_v0.2.git
cd OpenDwarfFortress_v0.2
pip install -r requirements.txt
python main.py

Pour jouer :
	-ZQSD pour se déplacer
	-TAB pour voler
	-clic droit pour poser un cube (selection dans l'inventaire avec le pavé numérique)
	-clic gauche pour detruire un cube
	-C pour prendre une capture 



Modifications :

Le 2015/12/13 :
	-compatibilite avec texture minecraft
	-augmentation blocs ( eau et roc)
	-generation plus realiste
	-correction bug seed terrain plat
	-correction bug apparition dans un bloc

Le 2015/12/12 :
	-empecher la capture de la souris pendant le chargement
	-fonctionnalitée de capture d'écran
	-generation du terrain avec noise
	-ajout d'une seed pour la generation
	-clavier AZERTY

La partie graphique du programme est basée sur le programme Open-Source de Michael Fogleman voir https://github.com/fogleman/Minecraft
