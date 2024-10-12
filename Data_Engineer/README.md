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

Veuillez vous assurer que ce découpage est correctement réalisé avant de transmettre le dataset à l'équipe de labélisation.

Date Limite : 14 octobre 2024
