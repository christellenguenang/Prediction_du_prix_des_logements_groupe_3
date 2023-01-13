# Prediction_du_prix_des_logements_groupe_3

Prédire le prix du logement est aussi utile pour le vendeur que l’acheteur. Le premier en a besoin pour connaitre l’opportunité d’investir dans l’immobilier, 
c’est-à-dire le profit qu’il peut espérer avoir au regard des coûts actuels. Quant au second, il voudrait savoir la somme qu’il lui faut pour s’octroyer un 
logement avec des caractéristiques données. Un tel problème peut être résolu à l’aide d’une masse critique de données statistiques sur la vente et 
les caractéristiques du logement. Cette résolution se fait en établissant une relation mathématique optimale entre le prix et les caractéristiques du logement.
Ainsi, pour tout nouveau logement non encore vendu, cette relation peut être utilisée pour faire une estimation du prix.
Le site internet de compétition de machine learning, Kaggle, fournit des données permettant d’effectuer un tel exercice.
Il s’agit de données portant sur le prix et diverses caractéristiques du logement de la ville d’Ams dans l’Etat de l’Iowa aux Etats Unis.
Selon plusieurs agences immobilières et le professeur François Rosiers, professeur titulaire dans le département de finance, assurance et immobilier 
à l’université de Laval, les caractéristiques importantes qui agissent sur la valeur de l’immobilier sont :
-	 L’emplacement
-	L’âge de la maison
-	La grandeur
-	Les rénovations récentes
-	Les attributs de luxe (terrasse, jardin, garage, piscine, place de stationnement privé, climatisation, plancher de bois massif)
A cet égard, quelle expression mathématique peut-on établir pour avoir une approximation du prix du logement en fonction des différentes caractéristiques ? 
L’objectif de notre travail est de prédire le prix des maisons à Ames en utilisant les modèles de machine Learning. 

Méthodologie

La méthodologie de travail est de précéder tout d’abord à un traitement de la base de données. 
S’ensuit une analyse exploratoire pour dégager les distributions des variables et ressortir les relations préliminaires qui les lient. 
Cette exploration permettra en outre d'avoir une idées des transformations à faire sur les variables afin de mieux les utiliser dans le modèle.
Il s’agira de faire des transformations pour avoir une relation linéaire entre le prix du logement et les variables quantitatives et ordinales. 
Pour les variables catégorielles, il est nécessaire de regrouper les modalités de réponse qui se ressemblent pour réduire le nombre de variables 
dans le modèle tout en gardant le maximum de l’effet discriminatoire. 
Les données pour cette modélisation sont labellisées et le volume de la base de données est relativement réduit, le modèle doit donc être du type 
supervised learning. 
Par ailleurs, la variable à prédire étant quantitative c’est une régression linéaire qui convient mieux. 
Ainsi, après avoir fait une bonne compréhension des variables avec la statistique descriptive et fait les transformations nécessaires, nous concevrons
quatre modèles, deux modèles linéaires (régression linéaire et Ridge) et deux modèles ensemblistes (random forest et gradient boosting).


