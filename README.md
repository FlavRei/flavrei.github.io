# Présentation
Voici mon Portfolio contenant mes projets de Data Science réalisés sur mon temps personnel. Les sujets de ces projets sont inspirés des domaines qui m'intéressent au quotidien et avaient pour objectif de m'apprendre et m'entraîner à utiliser les différents modèles incontournables en Data Science.

# Projets

### Music Finder
L'objectif de ce projet est de proposer une application affichant une liste de musiques en fonction de différents critères choisis par l'utilisateur comme le genre, l'émotion ou encore la décennie.  

Pour réaliser ce projet, je suis parti d'un dataset contenant différentes données sur une grande liste de musiques comme la valence, l'intrumentalitée, la danceabilitée, l'énergie, etc.  

Pour définir le critère d'émotion, j'ai utilisé la méthode KMeans pour former 5 clusters à partir des données musicales du dataset.  

Pour utiliser le modèle, j'ai développé une application Streamlit que déployée sur Render.  

L'application est disponible à l'adresse suivante :  
https://music-finder-g9mj.onrender.com  

![Music Finder](/assets/img/music-finder.png)  

La réalisation de cette application m'a permis d'apprendre à développer un projet de Data Science de A à Z, allant de la sélection d'un dataset à son nettoyage, en passant par l'analyse des données et de leur transformation, puis en développant une application Web pour utiliser le modèle construit, et enfin en déployant le projet avec Docker en passant par la plateforme Render.
