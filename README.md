# python-data-analysis
Allano Xavier - date: 15/02/2019
Python for data-science - devoir_maison - Cardiotocography

But du readme: expliquer le contexte et les objectifs

Contexte:
Création d'un script python qui automatise toute la procedure de modelisation de la base de donnée.

La base de donnée: Cardiotocography / Fichier CTG.xls récupéré sur internet:
https://archive.ics.uci.edu/ml/datasets/Cardiotocography

La cardiotocographie est utilisée pour surveiller l'etat de santé d'un foetus 
lors de la phase de travail qui precede l'accouchement.
La cardiotocographie est une analyse faite à partir de 2 données de base:
- Le rythme cardiaque du foetus
- L'intensité des contractions

De ces données sont déduites les autres features: nombre d'accelerations du rythme cardiaque,
nombre de décroissances legères, sevères ou prolongées, etc...

Objectifs:
Automatiser la procedure de modelisation afin de pouvoir prédire si l'etat de santé du foetus est normale ou non.
L'indicateur cible NSP dans le fichier CTG.xls prend 3 etats: normal, suspect ou pathologic

Dans un premier temps nous travaillons sur cette cible à 3 états:
- Exploration des données
- Visualisation des données avec des graphiques réalisés avec Matplotlib, Seaborn ou Bokeh
- Test de plusieurs algoritmes et comparaison des performances

Dans un deuxième temps nous travaillons sur une cible binaire en regroupant les états suspect et pathologic
- 0: état de santé normale  / 1: état de santé suspect ou pathologic 
- Visualisation des performances avec une courbe ROC
- La courbe ROC est une façon visuelle d'inspecter les performances d'un classifieur binaire (0/1)

