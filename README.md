# 📊 Optimisation de la performance du service client

### Contexte

Dans un environnement où le service client est fortement sollicité, la maîtrise des flux de contacts est essentielle pour garantir une expérience client fluide et maintenir la performance opérationnelle.\
Ce projet vise à analyser les interactions abonnés afin d’identifier des axes concrets d’amélioration du service client.

### Problématique

Comment évoluent les contacts abonnés et quels leviers activer pour optimiser la performance du service client ?

### Données utilisées
+ Volume de contacts (par jour)
+ Canaux (téléphone, email, chat)
+ Motifs de contact (technique, résiliation, facturation, information)
+ Temps moyen de traitement 
+ Taux de résolution

### Méthodologie 
+ Nettoyage et préparation des données (Excel /Power Query)
+ Analyse exploratoire (tendances, saisonnalité)
+ Analyse par canal
+ Analyse des motifs de contact
+ Identification des pics d’activité
+ Mise en relation avec la performance (temps, volume…) 

### Aperçu du Dashboard
<img width="1500" height="858" alt="Dashboard_perf service client" src="https://github.com/user-attachments/assets/9ce834bf-f4df-480d-ace9-c9fc241564dc" />

### Insights clés

L’analyse met en évidence plusieurs éléments structurants :

- **Un volume élevé de contacts (33 394)** traduisant une forte sollicitation du service client
- **Un temps moyen de traitement de 10 minutes**, indicateur clé d’efficacité opérationnelle
- **Un taux de résolution de 79,62%**, laissant apparaître une marge d’amélioration

:mag: **Analyse par canal**
- **Le chat est le canal le plus utilisé**, suivi du téléphone puis de l’email
- **Le téléphone présente un taux de résolution plus faible**, malgré un temps de traitement relativement élevé\
👉 Indice d’une inefficacité ou d’une complexité des demandes traitées via ce canal.

:mag: **Analyse par motif** 
- Les demandes liées à **l’information et au technique** génèrent le plus de contacts
- Les motifs comme la facturation et la résiliation restent significatifs\
👉 Ces volumes suggèrent des axes d’amélioration côté expérience client ou clarté des offres

:mag: **Évolution temporelle**
Une baisse progressive des contacts entre janvier et mars\
👉 Peut indiquer une amélioration des process… ou une variation saisonnière à creuser.

### Recommandations

Sur la base de ces analyses, plusieurs leviers d’optimisation peuvent être activés :

+ Renforcer le chat pour absorber les demandes simples, tout en surveillant les écarts pour détecter toute dégradation future
+ Améliorer la résolution au premier contact, notamment sur le canal téléphonique
+ Créer une FAQ ou base de connaissance sur les motifs récurrents (information, technique)
+ Optimiser la gestion des ressources en fonction des volumes observés

🛠️ **Outils utilisés**
+ Mockaroo (simulation de données)
+ Excel & Power Query (préparation des données, analyse & visualisation)
    
