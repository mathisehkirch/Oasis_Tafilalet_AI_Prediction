# Data Engineer - Instructions

Instructions 1 : 30/09/2024

En tant que Data Engineer, vous devez soumettre un premier livrable, faisant office de premier draft pour une description détaillée du jeu de données du projet (lien de la base de données uniquement accessible avec une adresse eigsica) [https://drive.google.com/drive/folders/12JSV8jCCBftZ5bF6Ci2Lk65XtKiDcolv?usp=sharing] . Ce rapport doit contenir les éléments suivants :

## Informations clés

La region couverte.
Le nombre d'images disponibles.
La taille de chaque image.
Le poids des images en mégaoctets (Mo).
La résolution spatiale, temporelle et spectrale des images.
Le satellite d'origine des images. (Ici Landsat 4 et 8)
La signification des noms de fichiers.
Le format des fichiers ...

## Critique de la Base de Données :
Évaluez les limitations de la base de données. Réfléchissez aux points suivants :

Quelles sont les lacunes potentielles dans les données ?
Y a-t-il des problèmes de qualité ou de couverture ?
Comment ces limitations pourraient-elles affecter le projet ?

## Affichage de la Base de Données 
Écrivez un code pour afficher les images du jeu de données. Par exemple, vous pouvez utiliser le framework Rasterio de Python. 

Date Limite : 07 octobre 2024



----------------------------------------------------------------------------------------------------------------------------------

Instruction 2 : 12/10/2024

Les data engineers doivent en urgence préparer le dataset d'ici ce lundi afin de pouvoir démarrer la phase de labélisation. Vous devez découper, à l’aide de QGIS, une partie du dataset correspondant à environ 10 années d'images. Les coordonnées à utiliser pour le découpage sont les suivantes :

301545.0000, 403215.0000, 3445395.0000, 3547065.0000 [EPSG:32630].

Pour effectuer le découpage de plusieurs fichiers en même temps selon le même cadre, vous pouvez vous inspirer de ce tutoriel :
https://www.youtube.com/watch?v=ffdgVGA_mk4.

En complément, vous devez également découper chacune des 10 images en 4 petites images (d'environ 300 x 300 pixels) couvrant 3 régions hétérogènes (par exemple, avec une zone de Sahara mélangé avec une zone d'oasis) et 1 région homogène (une fois oasis, une fois Sahara, une fois une structure artificielle comme une maison). Vous obtiendrez ainsi un total de 40 images.

Pour cela , vous pouvez  créer 8 masques : 3 masques fixes spatialement pour les régions hétérogènes et 5 masque pour les régions homogènes (car nous avons 5 classes). 
Les classes retenues sont : oasis (végétation), eau, erg (Sahara sableux), reg (Sahara rocheux), et terrain artificiel (panneaux solaires, routes, bâtiments, etc.).

Veuillez vous assurer que ce découpage et la création des masques sont correctement réalisés avant de transmettre le dataset à l'équipe de labélisation.

Date Limite : 14 octobre 2024

----------------------------------------------------------------------------------------------------------------------------------

Instruction 3 : 16/10/2024


Vous êtes prié de terminer au plus vite la labelisation des images. Cependant, faites attention à être cohérent dans votre labellisation et vérifiez systématiquement vos résultats après chaque labélisation. Une labelisation précise est essentielle pour garantir la qualité des modèles que vous développerez. N'oubliez pas de documenter ce que vous faites.

Date Limite : 23 octobre 2024
