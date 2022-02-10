# P8_LBo_Deployez_Modele_Cloud
**8ème et dernier projet dans le cadre de la formation de Data Scientist d'OpenClassRoom**

## deployez un modèle dans le cloud

Pour récupérer les éléments de ce projet : git clone https://github.com/elbo7777/P8_LBo_Deployez_Modele_Cloud.git

Le jeu de données est un ensemble d'images de fruits et de labels associés : https://www.kaggle.com/moltean/fruits

un traitement **local** sur une machine VM XUBUNTU via VIRTUALBOX a été mis au point sur l'ensemble des données images à traiter avant de basculer l'ensemble de l'arhcitecture traitement et données dans le cloud sur AWS => ces traitements correspondent au programme pyspark **P8_LBOIN_Version_Traitement_MachineVM_XUBUNTU_VIRTUALBOX.ipynb**

à executer sur une machine XUBUNTU en installant les données images de fruits et légumes dans le répertoire '/media/sf_Public/Fruit-Images-Dataset/Training/', sf_Public étant un disque partagé entre windows et la machine VM XUBUNTU pour ne pas alourdir l'espace disque de la machine VM en local.

Le passage à l'échelle est en cours de finalisation
