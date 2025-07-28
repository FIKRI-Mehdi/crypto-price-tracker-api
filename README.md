📈 Crypto Price Tracker – Analyse automatisée des cours BTC & ETH
🧠 Contexte
Le marché des cryptomonnaies est extrêmement volatil, avec des fluctuations pouvant survenir en quelques minutes. La capacité à collecter, structurer et analyser ces données en temps réel est une compétence clé pour un analyste de données.

Ce projet s’inscrit dans une démarche de montée en compétences autour :

de l'extraction de données via API,

de la gestion de données temporelles,

et de la visualisation de données financières.

🛠️ Solution
Ce notebook Python automatise la collecte de données sur les cryptomonnaies à l’aide de l’API de CoinMarketCap. Il se concentre sur deux actifs majeurs : Bitcoin (BTC) et Ethereum (ETH).

Étapes du projet :

Connexion à l’API CoinMarketCap via la bibliothèque requests

Extraction des données pour BTC et ETH toutes les minutes

Stockage des données dans un fichier .csv pour conservation historique

Structuration des données avec pandas : nettoyage, normalisation, horodatage

Visualisation dynamique avec seaborn pour identifier les tendances

✅ Résultats
⏱️ Collecte automatisée : les données sont récupérées toutes les minutes via une boucle Python.
💾 Stockage structuré : chaque nouvelle ligne ajoutée contient un horodatage et les prix actualisés.
📊 Visualisation claire : les variations de prix sont tracées dans le temps pour un suivi rapide.
📂 Prêt à l’emploi : le notebook peut facilement être réutilisé pour d'autres cryptos ou périodes.

📎 Exemple de graphique généré
![alt text](https://github.com/FIKRI-Mehdi/crypto-price-tracker-api/blob/main/Dashboard_BTC_ETH.png)

🚀 À propos
Ce projet fait partie de mon portfolio Data Analyst. Il illustre mes compétences en :

collecte de données via API,

manipulation de données temporelles,

automatisation de tâches,

visualisation avancée avec seaborn.

👉 N’hésitez pas à consulter le notebook Crypto_API_Notebook_finished.ipynb pour découvrir le code complet.

📊 Création de Dashboard Power BI
Une fois les données collectées et structurées, elles sont importées dans Power BI pour une visualisation interactive.

Éléments du dashboard :

Graphiques de suivi du prix de BTC et ETH mis à jour toutes les 5 minutes

Filtres dynamiques sur les symboles (BTC, ETH, etc.)

Personnalisation du design pour un rendu type Figma (fonds, bordures, ombres)

Formatage temporel des horodatages à la minute près

Cartes de résumé avec le dernier prix connu par actif

Objectif : offrir une interface claire, moderne et réactive pour explorer visuellement les tendances de prix des cryptomonnaies.
