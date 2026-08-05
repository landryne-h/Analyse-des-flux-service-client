# 📊 Optimisation de la performance du service client

### Contexte

Dans un environnement où le service client est fortement sollicité, la maîtrise et l’analyse des flux de contacts sont essentielles pour optimiser l’expérience utilisateur et améliorer l’efficacité opérationnelle.

Ce projet vise à analyser les interactions abonnés afin d’identifier les principaux facteurs de sollicitation du service client et proposer des leviers d’optimisation.

### Problématique

Comment évoluent les contacts abonnés et quels leviers actionner pour améliorer la performance opérationnelle et la qualité de service ?

### Données utilisées
+ Volume de contacts (par jour)
+ Canaux (téléphone, email, chat)
+ Motifs de contact (technique, résiliation, facturation, information)
+ Temps moyen de traitement 
+ Taux de résolution\
  
Voici le Dataset : [Dataset](https://github.com/landryne-h/Analyse-des-flux-service-client/blob/dc41956b72155cb0563e478a2dacff9a2e9a76f1/MOCK_DATA.csv)

### Méthodologie 
+ Nettoyage et préparation des données
+ Analyse exploratoire des tendances et saisonnalité
+ Analyse des performances par canal
+ Analyse des motifs de contact
+ Identification des pics d’activité
+ Corrélation entre volume, traitement et efficacité 

### Aperçu du Dashboard
<img width="1500" height="858" alt="Dashboard_perf service client" src="https://github.com/user-attachments/assets/9ce834bf-f4df-480d-ace9-c9fc241564dc" />

Accéder au fichier Excel ici : [Rendu](https://github.com/landryne-h/Analyse-des-flux-service-client/raw/ebdb7820e70375570884dd5e8df84a2c36f52c57/Analyse%20des%20Flux%20Service%20Client.xlsx)\
Accéder au Dashboard Power BI ici : [Voir](https://github.com/landryne-h/Analyse-des-flux-service-client/blob/main/Analyse%20des%20flux%20de%20service%20clients.pbix)

### Insights clés

L’analyse met en évidence plusieurs éléments structurants :

- **Un volume élevé de contacts (33 394)** traduisant une forte sollicitation du service client
- **Un temps moyen de traitement de 10 minutes**, indicateur clé d’efficacité opérationnelle
- **Un taux de résolution de 79,62%**, laissant apparaître une marge d’amélioration

:mag: **Analyse par canal**
- **Le chat est le canal le plus utilisé**, suivi du téléphone puis de l’email
- **Le téléphone présente un taux de résolution plus faible**, malgré un temps de traitement relativement élevé\
👉 Cela suggère une complexité plus importante des demandes traitées par téléphone et un potentiel de réallocation vers des canaux plus efficaces.

:mag: **Analyse par motif** 
- Les demandes liées à **l’information et au technique** sont les plus fréquentes
- Les motifs "facturation" et "résiliation" restent significatifs\
👉 Ces volumes suggèrent des axes d’amélioration côté expérience client ou clarté des offres

:mag: **Évolution temporelle**
Une baisse progressive des contacts entre janvier et mars\
👉 Peut indiquer une amélioration des process… ou un effet saisonnier à confirmer avec des données complémentaires.

### Recommandations

Sur la base de ces analyses, plusieurs leviers d’optimisation peuvent être activés :

+ Renforcer le chat pour absorber les demandes simples, tout en surveillant les écarts pour détecter toute dégradation future
+ Améliorer la résolution au premier contact, notamment sur le canal téléphonique
+ Créer une FAQ ou base de connaissance sur les motifs récurrents (information, technique)
+ Optimiser la gestion des ressources en fonction des volumes observés

🛠️ **Outils utilisés**
+ Mockaroo (génération de données)
+ Excel & Power Query (préparation des données, analyse & visualisation)
+ Power BI
    
