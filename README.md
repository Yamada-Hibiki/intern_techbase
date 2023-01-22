# intern_techbase
## Le background
J'ai effectué un stage de 4 mois en 2022 au Japon dans le machine learning chez Tech-Base. 
## L'objectif
L'objectif de ce programme de traitement d'image, c'est de povoir identifier les légumes (avocado, apple, broccoli, cabbage, pepper, pineapple, potato, tomato). 
En mettant en place ce système à la caisse, les clients pourront finir automatiquement l'addition en moins de temps.
## Techniques utilisées
Python, Tensorflow, Matplotlib, réseaux de neurones
## Le résultat
Final accuracy : 0.89.
Il se trouve que le système a du mal à distinguer entre la racine de broccoli et la peau d'avocat. J'ai augmenté le nombre de fois d'apprentissage pour chaque couche 
mais cela a baissé le "accuracy" global. J'ai rencontré le même problème pour les pommes et les tomates.
