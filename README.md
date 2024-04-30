# Analyse de la consommation d’électricité dans la province du Québec

# Aperçu du projet
Ce répertoire présente les résultats du projet d'analyse de la consommation énergétique dans la province du Québec. 
L'objectif de ce projet est décrire la consommation énergétique par Région administrative et par Secteur d'Activité durant la période allant de janvier 2016 à décembre 2023.
# Contenus
Dans ce répertoire, vous trouverez 1 fichier IPYNB présentant les résultats de cette analyse, de la collecte de donnée à l'analyse descriptive.
# Introduction
Dans ce travail, nous allons croisé les données de consommation d’électricité au Québec par secteur d’activité avec les données climatiques pour mette en évidence des tendances ou toute information pouvant contribuer à une meilleure gestion des ressources énergétiques.
# Méthodologie
#### • Collecte de données :
Les données ont été collectées à partir de sources publiques
Données de consommation électrique : https://www.hydroquebec.com/documents-donnees/donnees-ouvertes/historique-consommation-secteur-activite/  
Données climatiques : https://changements-climatiques.canada.ca/donnees-climatiques/#/sommaires-climatiques-mensuels  
Données de géolocalisation des régions administratives : https://www.donneesquebec.ca/recherche/dataset/decoupages-administratifs  
#### • Analyse de données
Analyse exploratoire des données 
- Secteurs d'activité : Agricole, Commercial, Industriel, Institutionnel et Résidentiel
- Régions administratives : Abitibi-Témiscamingue, Bas-Saint-Laurent, Capitale-Nationale, Centre-du-Québec, Chaudière-Appalaches, Côte-Nord, Estrie,
Gaspésie--Îles-de-la-Madeleine, Lanaudière, Laurentides, Laval, Mauricie, Montréal, Montérégie, Nord-du-Québec, Outaouais, et Saguenay--Lac-Saint-Jean
#### • Visualisation des données
- Utilisation de diagramme circulaire, boite à moustache, graphique linéaire et histogramme pour réprésenter la consommation suivant le secteur d'activité et l'année 
- Utilisation de Folium pour cartographier les régions administratives suivant leur consommations électrique
# Conclusion
Sur la base de l'analyse, les conclusions suivantes peuvent être tirées :
• Le secteur ayant la plus forte consommation est le secteur Résidentiel, suivi du secteur Industriel, Commercial, Institutionnel et enfin agricole.

• Par année, la consommation suit une variation saisonnière : très forte en hiver (décembre à mars), décroit durant le printemps et l'été (en particulier de mai à Septembre) puis recommence à croitre pour atteindre un nouveau pic en hiver.

• Les années 2018, 2019 et 2022 présentent des pics de forte consommation et sont marquées par des températures minimales moyennes les plus basses soient respectivement -12,54° , -12,14° et -12,19°

• Tout secteur confondu, sur la période de 2016 à 2023, les régions ayant le plus consommé d'énergie sont Montréal, Montérégie, Capitale-Nationale et Côte-Nord avec des consommations dépassant les 100 milliard de kWh

•  Sur la période de 2016 à 2023, les régions administratives consommant le plus d'énergie sont :
- Secteur Résidentiel : Montréal et Montérégie   
- Secteur Industriel : Côte-Nord et Montérégie  
- Secteur Commercial : Montréal et Montérégie  
- Secteur Institutionnel : Montréal et Montérégie   
- Secteur Agricole : Montérégie et Chaudière-Appalaches

# Recommandation 
•  Faire une analyse plus approfondies des secteurs d'activité afin d'identifier les facteurs entrainant la baisse ou la hausse de la consommation électrique
•  Procéder une analyse prédictive de la consommation électrique de 2024 et 2025 en croisant les données de consommations aux facteurs identifiés

# Annexe
• Les données utilisées dans ce projet ont été obtenues via des sources publiques.
