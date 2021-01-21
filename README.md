# Kooping-Action-Recognition

## Introduction

Objectives

## Tracking in video

### Benchmark
### Top Down approach
Cropping
### Results

## Pose Estimation

### Benchmark
### OpenPose
OpenPose semble très satisfaisant, tant que les personnes ne sont pas trop petites sur l’image. Des paramètres d’agrandissement sont possibles mais amènent la reconnaissances de squelettes là où il n’y a personne
Vidéos : https://drive.google.com/drive/folders/1iKisd4lKeix71umSCyTbABT1Kfpxt6BX?usp=sharing 

Nous avons essayé de raffiner le modèle sur la base de données JTA, mais la documentation hasardeuse de la base de données et des implémentations de openpose sous tensorflow, ont compliqué les choses.
Le format de compression des données, nécessaire pour l'entraînement, ne nous permet pas de stocker un nombre important de vidéos pour le raffinement des poids (on a des fichiers binaires allant jusqu’à 50Go). Ayant jugés les résultats avec OpenPose satisfaisants pendant la réunion, nous nous consacrons désormais à la reconnaissance d’actions. Nous pourrons toujours revenir sur cette partie s’il nous reste du temps après avoir abouti sur la partie suivante.

### Results


## Action Recognition

### Benchmark
### Dataset
### VAE
### Results


## Further work

Replace OpenPose
Fill DataSet
