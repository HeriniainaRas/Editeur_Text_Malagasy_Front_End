# Editeur_Text_Malagasy_Front_End

>Machine Learning INFO5 2024-2025 **ISPM**
# QUICKSILVER 🤖

# Thème :  Éditeur de Texte Augmenté par l'IA pour le Malagasy
# Date : 24-03-26

## Institut Supérieur Polytechnique de Madagascar : http://www.ispm-edu.com/
Membre de l'équipe **(IGGLIA 5)** et le rôle respectif de chacun: 
  * **RANDRIANOELINA Liantsoa Harimisa                       ,n°14** : chargé de la creation du model 'Analyse de Sentiment' et son intégration.
  * **ZAFIARISON Koloina Emile                               ,n°16** : chargé de l'intégration front et développement endpoint pour faire la prédiction + déploiement.
  * **RANDIMBINIRINA RAKOTOMANANA Yusha Andry Ny Aina        ,n°19** : chargé de la creation des modeles 'Correcteur Orthographique' et 'Reconnaissance d'Entités (NER)'
  * **RASOLONJATOVO Zo Heriniaina                            ,n°23** : chargé de la creation des modeles 'Autocomplétion (Next Word Prediction)' et 'Synthèse Vocale (TTS)'

## Lien de DEMO video version 1: https://drive.google.com/drive/folders/17NiQm8c8vZACuYLdDhBQGDsOXG9I03rs?usp=sharing

## Lien Front-End de l'application : https://malagasy-editor.vercel.app/
## Lien source-code Front-End : https://github.com/koloinaZafiarison/interfaceMalagasyTextEditor
----------------------------------------------------------------------------------------------------
## Lien Back-End de l'application : https://github.com/koloinaZafiarison/malagasyApi2026/tree/main
## Lien Back-End modele IA : https://github.com/HeriniainaRas/Editeur_Text_Malagasy_Back_End


## description des fonctionnalités IA  : 
  * **Modèle IA d'autocomplétion et prédiction de mot suivant**: un modèle d'Intelligence Artificielle qui permet de prédire les lettres composantes d'un mot lorsqu'on tape au clavier et ensuite prédire l'éventuel mot suivant du mot correspondant. 
  * **Modèle IA d'analyse de sentiment**: un modèle qui permet d'interpreter si une phrase écrite exprime une connotation positive ou négative.
  * **Modèle IA correcteur orthographique, de vérification phonotactique, et de lémmatisation**: un modèle qui permet de donner des suggestions et de corriger des mots incorrects, de vérifier si les mots respectent les régles grammaticales de la langue malagasy, et enfin d'extracter la lemme des mots malagasy.
  * **Modèle IA de synthèse vocale**: un modèle IA "text to speech" qui permet de lire avec un accent local malagasy un texte écrit sur l'application. On a pa encore pu intégrer le modèle dans l'interface graphique mais l'entraînement est déjà fait.
  * **Modèle IA de reconnaissance d'entités(NER)**: un modèle qui permet de détecter s'il y a des personnalités spécifiques dans le phrases Malagasy et les classes selon leurs types. Un modèle que nous allons aussi implémenter dans l'interface graphique ultérieurement.
    

## Bibliographie : 
  * Dataset Autocompletion : https://huggingface.co/datasets/Lo-Renz-O/malagasy-sentence
  * Dataset Synthèse Vocale : https://huggingface.co/datasets/hasiniaina/malagasy-female-speech-dataset
  * Dataset Correcteur Orthographique/ Vérification à base de règles/ Lemmatisation : https://tenymalagasy.org/bins/rootLists, https://mg.wikipedia.org/w/api.php, https://raw.githubusercontent.com/christos-c/bible-corpus/master/bibles/Malagasy.xml
  * Analyse de Sentiment : https://huggingface.co/datasets/Lo-Renz-O/vaovao_malagasy_sentiment_corpus + **scraping** sur https://tenymalagasy.org/bins/rootLists
  *  Reconnaissance d'Entités (NER) : https://simplemaps.com/data/mg-cities
