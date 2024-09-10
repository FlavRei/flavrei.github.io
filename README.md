# Présentation
Voici mon Portfolio contenant mes projets de Data Science réalisés sur mon temps personnel. Les sujets de ces projets sont inspirés des domaines qui m'intéressent au quotidien et avaient pour objectif de m'apprendre et m'entraîner à utiliser les différents modèles incontournables en Data Science.

# Projets

### Music Finder
L'objectif de ce projet est de proposer une application affichant une liste de musiques en fonction de différents critères choisis par l'utilisateur comme le genre, l'émotion ou encore la décennie.  

Pour réaliser ce projet, je suis parti d'un dataset contenant différentes données sur une grande liste de musiques comme la valence, l'intrumentalitée, la danceabilitée, l'énergie, etc.  

Pour définir le critère d'émotion, j'ai utilisé la méthode KMeans pour former 5 clusters à partir des données musicales du dataset.  

Pour utiliser le modèle, j'ai développé une application Streamlit que déployée sur Render.  

L'application est disponible à l'adresse suivante :  
https://flavrei-music-finder.streamlit.app/    

![Music Finder](/assets/img/music-finder.png)  

La réalisation de cette application m'a permis d'apprendre à développer un projet de Data Science de A à Z, allant de la sélection d'un dataset à son nettoyage, en passant par l'analyse des données et de leur transformation, puis en développant une application Web pour utiliser le modèle construit, et enfin en déployant le projet avec Docker en passant par la plateforme Render.

### Music Classifier
L'objectif de ce projet est de proposer une application devinant le style des musiques qu'on lui propose.  

Pour réaliser ce projet, j'ai utilisé un dataset contenant 1000 fichiers audio réunis équitablement dans 10 catégories représentant les genres musicaux (blues, classique, country, disco, hiphop, jazz, metal, pop, reggae, rock).  

J'ai développé 3 modèles de classification sur différentes caractéristiques récupérées à partir des fichiers audio.  
Les 3 modèles développés étaient le LSTM, GRU et le CNN.  
J'ai ensuite entraîné ces modèles pour comparer les performances. Le modèle CNN était celui offrant de meilleurs résultats et donc c'est celui qui a été conservé pour développer l'application.  

L'application est disponible à l'adresse suivante :  
https://flavrei-music-classifier.streamlit.app/  

![Music Classifier](/assets/img/music-classifier.png)  