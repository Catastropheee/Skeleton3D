Skeleton3D
==========

Source de la petite reprap française 
Je viens vous présenter mon petit projet reprap: la skeleton 3D

L’idée a germé dans ma tête après quelques mois d’utilisation de ma prusa i3, beaucoup de personnes dans mon entourage avaient envie de voir la bécane fonctionner mais ce n’est pas super facile de transporter une i3. De plus, j’ai constaté que j’utilisais très rarement l’entière surface d’impression et que la majorité de mes print se limite à une surface de 100x100.

Après avoir cherché une petite imprimante compacte, transportable et peu chère sur le wiki, j’ai décidé d’en concevoir une répondant à mes besoins faute d’en trouver une ! 
C’est-à-dire: transportable, robuste, évolutive, peu cher mais avec des impressions de qualité !

L'union faisant la force et augmentant la créativité, j’ai travaillé avec un ami possédant aussi une i3 qui a tout de suite accroché.

Nous avons par la suite, commencé par définir :
L’architecture de la machine 
- Pièces plastiques + tiges filetés Ø8 (?€)
- Déplacement de la hotend en X et Y (course 100x100) et du plateau en Z (course 100 à 150 mm)
- Mouvements axiaux + Extrusion
- 4 moteurs NEMA 17 de 40 mm et 4kg
- 1 extruder conçu pour être compact et en directdrive

Guidage axiaux :
- Classique avec des LM8UU

Hotend :
- Aluhotend 1.75mm (en cours de test)

Alimentation :
- 72W de pc portable

 736943COM.jpg
736943COM.jpg


Améliorations apportées au prototype :
->	Augmentation de la surface de guidage (2xLM8uu) au niveau de l’effort moteur (X et Y) pour supprimer le risque d’arc boutement
->	Augmentation de la surface de guidage du plateau Z (3x LM8uu) pour limiter la flexion
->	Augmentation de la surface de guidage de la hotend (4 x LM8uu) pour supprimer les jeux
->	Mise en place d’un plateau acier galva 15/10
->	Fixation par vis des endstop intégré aux pièces plastiques
->	Calibrage Z via une vis M4 réglable
