# Présentation
Voici mon Portfolio contenant mes projets de Data Engineering / Data Science réalisés sur mon temps personnel. Les sujets de ces projets sont inspirés de domaines qui me concernent et avaient pour objectif de m'apprendre et m'entraîner à utiliser les différents modèles incontournables en Data Science et surtout à savoir développer une application et la déployer dans le Cloud.

# Projets
### Cereals Price Prediction
L'objectif de ce projet est de proposer une application permettant d'avoir un aperçu de l'évolution du prix des céréales sur les années passées et également d'estimer une prédiction du prix des céréales dans les années futures.

Pour réaliser ce projet, j'ai récupéré depuis l'API FAOSTAT les données concernant le prix de 5 céréales de 1994 à 2023 en France.

Pour chaque céréale, j'ai entrainé un modèle Prophet sur ses données historiques afin qu'il donne une estimation haute, une estimation basse et une estimation moyenne de l'évolution du prix de la céréale concernée dans le futur.

Pour utiliser l'application, j'ai développé l'interface avec Streamlit. J'ai ensuite mis en place une CI/CD avec GitHub Actions pour déployer automatiquement l'application sur GCP.

L'application est disponible à l'adresse suivante : 
https://cereals-dashboard-258413365847.europe-west1.run.app

![Cereals Price Prediction](/assets/img/cereals-price-prediction.png)

### Music Finder
L'objectif de ce projet est de proposer une application affichant une liste de musiques en fonction de différents critères choisis par l'utilisateur comme le genre, l'émotion ou encore la décennie.  

Pour réaliser ce projet, je suis parti d'un dataset contenant différentes données sur une grande liste de musiques comme la valence, l'intrumentalitée, la danceabilitée, l'énergie, etc.  

Pour définir le critère d'émotion, j'ai utilisé la méthode KMeans pour former 5 clusters à partir des données musicales du dataset.  

Pour utiliser le modèle, j'ai développé une application Streamlit que déployée sur Render.  

L'application est disponible à l'adresse suivante :  
https://flavrei-music-finder.streamlit.app/    

![Music Finder](/assets/img/music-finder.png)  

### Music Classifier
L'objectif de ce projet est de proposer une application devinant le style des musiques qu'on lui propose.  

Pour réaliser ce projet, j'ai utilisé un dataset contenant 1000 fichiers audio réunis équitablement dans 10 catégories représentant les genres musicaux (blues, classique, country, disco, hiphop, jazz, metal, pop, reggae, rock).  

J'ai développé 3 modèles de classification sur différentes caractéristiques récupérées à partir des fichiers audio.  
Les 3 modèles développés étaient le LSTM, GRU et le CNN.  
J'ai ensuite entraîné ces modèles pour comparer les performances. Le modèle CNN était celui offrant de meilleurs résultats et donc c'est celui qui a été conservé pour développer l'application.  

L'application est disponible à l'adresse suivante :  
https://flavrei-music-classifier.streamlit.app/  

![Music Classifier](/assets/img/music-classifier.png)  

# Conclusion
La réalisation de ces applications m'a permis d'apprendre d'une part à développer des projets de Data Science de A à Z, allant de la sélection d'un dataset à son nettoyage, en passant par l'analyse des données et de leur transformation. 

Et d'une autre part, cela m'a permis de réaliser par moi-même leur déploiement dans le Cloud avec Docker en passant par la plateforme Render ou par GCP, notamment en réalisant une CI/CD avec GitHub Actions pour que le déploiement soit automatisé. Cela représente une compétence essentielle d'un Data Engineer afin de pouvoir déployer des projets en production.