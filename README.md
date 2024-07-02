# titanic-survival-rate

## Introduction

## Getting started
- Download dataset [here](https://drive.google.com/drive/folders/1eUIgWVpYd2USOJ96KXb94AfbN8dh_pHJ?usp=drive_link)
- Put data/ donwnloaded folder in root folder

## Watch
1) Qu’est ce que l’apprentissage automatique supervisé ?

    L'apprentissage automatique supervisé est une sous branche de l'apprentissage automatique qui consiste a entrainer des modèles de Machine Learning en lui donnant des données d'entrainement étiquetées
  
2) Qu’est ce que les données étiquetées (ou labellisées) ?
   
    Les donées étiquetées sont des données dont on connait a l'avance la sortie qui est attendue lors de la prédiction

3) En particulier, qu’est ce que la classification supervisée (ou méthode de classement) ?
    
    La classification supervisée est une sous branche de l'apprentissage automatique supervisé qui permet de prédire des catégories

4) Qu’est ce qu’on appelle un modèle d’apprentissage automatique ?
    
    Un modèle d'apprentissage automatique est un programme capable de trouver des modèles et de prendre des decisions a partir d'un jeu de données

5) Qu’est ce que les données d’entraînement ? Qu’est ce que l’entraînement d’un modèle de classification supervisée ?
    
    Les données d'entrainement sont les données servant a entrainer le modèle. L'entrainement consiste a executer un algorithme de machine learning sur un dataset et a optimiser l'algorithme pour obtenir certaines données en sortie

6) Qu’est ce que la donnée cible (ou le target) ?
   
    La donnée cible est la colonne du dataset que l'on cherche a prédire

7) A quoi sert la phase d’entraînement d’un modèle d’apprentissage automatique ?
    
    La phase d'entrainement sert a améliorer les performances du modèle

8) A quoi sert la phase de prédiction d’un modèle d’apprentissage automatique ?
   
    La phase de prédiction d'un modèle d'apprentissage automatique sert a donner en entrée des données que le monèle ne connait pas et a lui faire prédire une sortie
   
9)  Qu’est ce que le prétraitement des données et pourquoi est-il important à réaliser avant l’entraînement d’un modèle d’apprentissage automatique ?
    
    Le prétraitement des donnés est la phase de nettoyage des données. Elle est importante parce que la qualité des données est le facteur principal de la qualité des prédictions
    
10) Comment l’évaluation d’un modèle d’apprentissage automatique pour une tâche de classification peut-elle se faire ? Etudiez en particulier et seulement, la métrique d’accuracy. En quoi est-elle un indicateur de performance d’un modèle ?
    
    L'évaluation d'un modèle de machine learning pour une tache de classification peut se faire avec différentes métriques, comme l'accuracy, qui répond a la question suivante : Combien d'individus ont été correctement prédits? Sa formule est :
    <math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
        <mfrac>
            <mrow>
                <mi>T</mi><mi>P</mi><mo>+</mo><mi>T</mi><mi>N</mi>
            </mrow>
            <mrow>
                <mi>T</mi><mi>P</mi><mo>+</mo><mi>T</mi><mi>N</mi><mo>+</mo><mi>F</mi><mi>P</mi><mo>+</mo><mi>F</mi><mi>N</mi>
            </mrow>
        </mfrac>
    </math>
    ![Matrice de confusion](imgs/accuracy_matrix.webp)

    | Actual \ Predicted | Positive  | Negative |
    |--------------------|-----------|----------|
    | Positive           | TP        | FN       |
    | Negative           | FP        | TN       |

    - TP : True Positive
    - FN : True Negative
    - FP : False Positive
    - TN : True Negative

11) Qu’est ce que l’AutoML et pourquoi est-il pertinent pour vous en tant que débutant dans le domaine de l’intelligence artificielle ?

    AutoML (Automated Machine Learning) est une technologie qui automatise les étapes de création et de déploiement de modèles de machine learning, telles que le prétraitement des données, la sélection de caractéristiques, la sélection et l'optimisation des modèles, ainsi que leur évaluation.
    
    Il est pertinent pour les débutants en IA car il simplifie et rend accessible le processus de machine learning, permettant de se concentrer sur l'apprentissage des concepts de base sans se perdre dans les détails techniques complexes.
    

12) Qu’est ce qu’un arbre de décision pour la classification supervisée ? Comment fonctionne–t-il ? (félicitations, vous avez appris votre premier modèle d’intelligence artificielle !).
    
    Un arbre de décision est un modèle de machine learning utilisé pour la classification supervisée qui divise les données en sous-groupes basés sur des critères de décision, représentés sous forme d'une structure arborescente.

    Il fonctionne en posant des questions successives sur les caractéristiques des données, divisant les données à chaque nœud jusqu'à ce que des décisions de classification soient prises aux nœuds terminaux.
