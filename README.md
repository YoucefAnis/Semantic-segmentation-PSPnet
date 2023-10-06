
# Segmentation sémantique des images de feuilles malades
Ce travail d’étude traite le sujet de la segmentation sémantique d'images. 

La segmentation d’images est une technique de vision par ordinateur qui consiste à découper de façon automatique une image en zones de pixels appartenant à une même classe d’objets.
La segmentation d’images se divise en deux types, la segmentation sémantique et la segmentation par instance.


Dans le cadre de ce projet, l'objectif principal était d’utiliser ou de mettre en œuvre l'approches PSPNet pour la segmentation sémantique des images de plantes malades.

La base de données que nous avons utilisée pour entrainer et tester le PSPNet est divisée en deux dossiers : le premier dossier, **"original_images"**, contient 451 images d'entraînement et 52 images de test. Le deuxième dossier, nommé **"mask_images"**, contient les masques de vérité terrain correspondant aux images originales.

## 1. Prérequis
Ce projet nécessite les packages suivants pour fonctionner :
* [Python 3](https://www.python.org/)
* [NumPy](https://numpy.org/)
* [MatPlotLib](https://matplotlib.org/)
* [Opencv](https://opencv.org/)
* [TensorFlow](https://www.tensorflow.org/?hl=fr)

## 2. Fichiers
Ce projet est composé des fichiers suivants:
* **PSPnet_for_semantic_segmentation.ipynb ->** Fichier principal qui contient le code.
* La base de données que vous pouvez télécharger depuis ce lien -> [**Base de données**](https://drive.google.com/drive/folders/1oL36dURG1fCZnDrWXwLB1qKbJNbzEwNR?usp=drive_link).

## 3. Execution du projet
1. Pour mettre en marche ce projet, téléchargez la base de données [**Base de données**](https://drive.google.com/drive/folders/1oL36dURG1fCZnDrWXwLB1qKbJNbzEwNR?usp=drive_link)
2. Importez et executez le fichier **PSPnet_for_semantic_segmentation.ipynb** dans Google Colab. Cela vous permettra de l'exécuter en utilisant le processeur graphique de colab, réduisant ainsi les temps d'apprentissage.

## 4. Résultats
![Résultat 1](https://github.com/YoucefAnis/Semantic-segmentation-PSPnet/blob/main/R%C3%A9sultats/R%C3%A9sultat%201.png "Résultat 1")

![Résultat 2](https://github.com/YoucefAnis/Semantic-segmentation-PSPnet/blob/main/R%C3%A9sultats/R%C3%A9sultat%202.png "Résultat 2")

![Résultat 3](https://github.com/YoucefAnis/Semantic-segmentation-PSPnet/blob/main/R%C3%A9sultats/R%C3%A9sultat%203.png "Résultat 3")

## 5. Références
* Garcia-Garcia, A., Orts-Escolano, S., Oprea, S., Villena-Martinez, V., & Garcia-Rodriguez, J. (2017). A review on deep learning techniques applied to semantic segmentation. arXiv preprint arXiv:1704.06857.

* Yan, L., Liu, D., Xiang, Q., Luo, Y., Wang, T., Wu, D., ... & Li, Q. (2021). PSP net-based automatic segmentation network model for prostate magnetic resonance imaging. Computer Methods and Programs in Biomedicine, 207, 106211.





