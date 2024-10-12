
# ML/DL Engineer - Instructions

Instructions 1 : 30/09/2024  
 
   Réalisez une première investigation sur les différentes méthodes utilisées pour la classification d'images satellites en vue de déterminer l'occupation du sol. 
   
   Votre enquête doit inclure :
   
1. Investigation dans la Littérature :

   - Méthodes de Classification :  
     - Deep Learning : Listez les modèles et architectures populaires (par exemple, CNN, U-Net, etc.).
     - Machine Learning : Mentionnez des méthodes traditionnelles (par exemple, SVM, Random Forest, etc.).
     - Méthodes Statistiques Simplifiées : Incluez des approches classiques comme le voisin le plus proche.

   - Supervisé vs Non Supervisé :  
     - Discutez des différences entre les approches supervisées (nécessitant des données labellisées) et non supervisées.
     - Indiquez des exemples de techniques pour chacune de ces approches.

      Discuter des avantages et limites de chaque méthode.

2. Entrées et Sorties :
   
  Quelles sont les données d'entrée et les sorties attendues pour chaque méthode ?


Date Limite : 07 octobre 2024




------------------------------------------------------------------------------------------------------------------------------------

Instruction 3 : 12/10/2024

En attendant que les images soient labélisées, je vous invite à  tester des modèles non supervisés en Machine Learning pour évaluer s'ils sont capables de réaliser un clustering sur une image pour créer un bon plan d'occupation. Afin d'éviter tout conflit de bibliothèques, je vous invite à installer les versions suivantes des bibliothèques :

- TensorFlow version : **2.17.0**
- Rasterio version : **1.4.1**
- Scikit-learn version : **1.5.2**
- GeoPandas version : **1.0.1**
- Matplotlib version : **3.7.1**
- NumPy version : **1.26.4**
- TensorFlow Keras version : **3.4.1**

Vous devrez  utiliser **Rasterio** pour importer les images satellites et les manipuler sous forme de tenseurs afin de faciliter l'intégration dans vos modèles de Machine Learning.

### Commandes d'installation avec `pip` :

```bash
pip install tensorflow==2.17.0
pip install rasterio==1.4.1
pip install scikit-learn==1.5.2
pip install geopandas==1.0.1
pip install matplotlib==3.7.1
pip install numpy==1.26.4
pip install keras==3.4.1
```

### Commandes d'installation avec `conda` :

Si vous utilisez **conda**, voici les commandes correspondantes pour installer ces bibliothèques avec les versions spécifiées :

```bash
conda install tensorflow=2.17.0
conda install rasterio=1.4.1
conda install scikit-learn=1.5.2
conda install geopandas=1.0.1
conda install matplotlib=3.7.1
conda install numpy=1.26.4
conda install keras=3.4.1
```

Date Limite : 14 octobre 2024

