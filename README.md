# 📊     Classification-des-vidéos-TikTok

[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📝 Description du Projet
L'objectif de ce projet était de Construire un modèle d'apprentissage automatique (machine learning) capable de déterminer si une vidéo contient une affirmation factuelle ou s'il s'agit d'une opinion. Ce qui permettra à TikTok de réduire l'accumulation des signalements d'utilisateurs et les hiérarchiser plus efficacement. Le modèle final de forêt aléatoire a fonctionné avec une précision de 86% et une exactitude de 72% déterminant quelles caractéristiques étaient les plus importantes pour séparer les low tippers des high tippers. 
D'après le modèle, la durée, la distance et le coût du trajet ont eu le plus d'influence sur la détermination
d'un pourboire généreux (>20%) par rapport à un pourboire non généreux (<20%).

## Compréhension du monde des affaires
├Selon salary.com, le salaire moyen d'un chauffeur de taxi new-yorkais est d'environ 45 000 dollars. 
Ce salaire est nettement inférieur à la valeur médiane d'un loyer de 6 500 dollars par mois. Il est important
de comprendre quels sont les facteurs qui encouragent les usagers à laisser des pourboires afin d'aider les chauffeurs à obtenir un salaire décent.
## Compréhension des données
Les données de la NYC Taxi and Limousine Commission proviennent de NYC.gov.
Les données comprenaient environ 408 000 trajets uniques et 18 caractéristiques. Les caractéristiques comprenaient des informations sur la durée et la destination du trajet, le fournisseur utilisé, les informations sur le péage et le type de paiement. Le Graphique à barres ci-dessous montre la répartition entre les usagers généreux (>20%) et les usagers non généreux dans l'ensemble des données.

![alt text](1.png)

 Dans le même ordre d'idées, une ingénierie des caractéristiques a été mise au point pour indiquer si un trajet a été effectué pendant les heures de pointe ou non. Plusieurs colonnes redondantes ont été supprimées et reformatées dans le type de données approprié.
 ## Évaluation de modèles
 Un modèle de Forêts d'arbres décisionnels comprenant 100 arbres décisionnels a été utilisé pour déterminer l'importance des caractéristiques dans la décision de donner ou non un pourboire généreux. Le graphique ci-dessous montre que la durée du voyage, la distance et le coût de la course sont les trois facteurs les plus importants pour déterminer qui donne un pourboire
 généreux et qui n'en donne pas. Le modèle global a atteint une précision de 86 % et une exactitude de 72%.

![alt text](2.png)

 ## Conclusion

Ce modèle peut aider les chauffeurs de taxi à savoir s'ils recevront un pourboire généreux ou non ; cependant, l'exécution d'un modèle paramétrique pour déterminer combien chaque variable influencera le prix réel du pourboire.
À l'avenir, l'ajout d'informations sur le comportement antérieur d'un passager en matière de pourboire pourrait également aider les parties prenantes à résoudre leur problème commercial.
