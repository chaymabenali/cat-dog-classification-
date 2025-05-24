# cat-dog-classification-
Ce projet met en œuvre un pipeline complet de vision par ordinateur pour classifier des images comme contenant un chat ou un chien. Il couvre la préparation des données, la segmentation d'objets à l'aide de YOLOv8, l'extraction de caractéristiques, et la classification via des modèles de Machine Learning classiques.

## Fonctionnalités

*   **Préparation Automatisée du Jeu de Données :** Division des images en ensembles d'entraînement et de test.
*   **Segmentation d'Objets Performante :** Utilisation de YOLOv8 (modèle `yolov8n-seg.pt`) pour segmenter précisément les animaux dans les images et générer des masques binaires.
*   **Extraction de Caractéristiques Multiples :**
    *   **Géométriques :** Aire, périmètre, rapport d'aspect, circularité.
    *   **Photométriques :** Moyenne et écart-type de l'intensité des pixels.
    *   **Texturales :** Énergie, homogénéité, entropie (basées sur la Matrice de Co-occurrence des Niveaux de Gris - GLCM).
*   **Classification par Machine Learning :** Entraînement et évaluation comparative de plusieurs modèles :
    *   Support Vector Machine (SVM)
    *   k-Nearest Neighbors (k-NN)
    *   Random Forest
    *   Régression Logistique
*   **Évaluation Détaillée des Modèles :** Métriques (Accuracy, Précision, Rappel, F1-Score), matrices de confusion, courbes d'apprentissage, courbes ROC/AUC.
*   **Analyse des Caractéristiques :** Visualisation des distributions, matrices de corrélation, et Analyse en Composantes Principales (ACP) pour comprendre leur pertinence.

* 

