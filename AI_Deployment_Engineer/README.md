
# Ingénieur Déploiement IA - Instructions

Instructions 1 : 30/09/2024

Dans le cadre de votre rôle, vous devez réaliser une première investigation sur le développement de la plateforme d'IA. Cette investigation doit porter sur les éléments suivants :

1. Fonctionnalités de la Plateforme :
   - Quelles sont les fonctionnalités essentielles à inclure ? Par exemple :
     - Affichage d'images satellites, à l'instar d'Earth Explorer : https://earthexplorer.usgs.gov/
     - Sélection d'une région spécifique à l'aide d'outils dédiés.
     - Intégration des modèles d'intelligence artificielle : 
       - Quels formats doivent être utilisés pour les modèles (par exemple, ONNX, TensorFlow SavedModel, etc.) ?
     - Affichage des résulats : indicateurs de performance clés (KPI) et des cartes d'occupation.

2. Technologies et Outils :
   - Quelles technologies et quels outils seront nécessaires pour le développement de la plateforme ?


Date Limite : 07 octobre 2024

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Instructions 2 : 12/10/2024

Dans le cadre du développement de la plateforme web, votre première tâche consiste à implémenter un bouton permettant d'importer les 7 bandes d'une image satellite (ou un fichier multibande). Ce bouton doit également générer et afficher une composition en vraies couleurs en combinant les bandes 2, 3 et 4.

Vous êtes libre de choisir les technologies pour réaliser cette tâche. Cependant, voici quelques technologies recommandées : Streamlit ou Flask pour le front/back end, Rasterio pour la manipulation des fichiers raster.

De plus, vous devez extraire la date contenue dans le nom des fichiers importés, l'afficher dans l'interface utilisateur, et sauvegarder à la fois l'image générée et la date dans une table dédiée de votre base de données.

Il est important que vous réfléchissiez à la base de données la plus adaptée à ce projet (Entre MySQL, PostgreSQL ou MongoDB), en tenant compte des besoins en matière de gestion des données (structurées ou non structurées).

Date Limite : 19 octobre 2024
