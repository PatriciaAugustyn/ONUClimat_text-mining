# Projet Text Mining : Analyse des Tweets de l’ONU Climat France

Ce projet, réalisé dans le cadre du cours de **Text Mining** en Licence 3 à la **Sorbonne Nouvelle** sous la supervision de *Loubna Serrar*, vise à analyser les tweets de l'ONU Climat France pour mieux comprendre leurs stratégies de sensibilisation sur les enjeux climatiques.

## Contexte et Objectifs

L'objectif de ce projet est d'utiliser les techniques de text mining pour extraire des informations utiles des tweets publiés par le compte **ONU Climat France** de 2015 à 2022. Nous cherchons à analyser l’évolution des thèmes, des émotions et de l’engagement du public autour des sujets climatiques et écologiques.

Les principales questions explorées sont :
- Quels thèmes sont les plus abordés par l'ONU Climat France pour sensibiliser le public ?
- Comment l'utilisation des hashtags et emojis influence-t-elle l'engagement des jeunes ?
- Quels sentiments dominent ces tweets (positifs, neutres, négatifs) ?

## Techniques Utilisées

Pour répondre à ces questions, nous avons utilisé les étapes et outils suivants :
- **Scraping** : récupération des tweets via la librairie `snscrape`.
- **Prétraitement des données** : nettoyage, tokenisation, suppression des mots vides (librairies `nltk` et `spacy`).
- **Text Mining** :
  - **Fréquence de termes et TF-IDF** pour identifier les mots-clés les plus pertinents.
  - **Analyse de Sentiment** pour évaluer les émotions exprimées dans les tweets.
  - **N-grams** et **bigrams** pour explorer les cooccurrences de mots et phrases clés.


## Résultats

Nos analyses montrent une prédominance de thèmes liés aux **actions climatiques** et **engagements écologiques**. L’utilisation de vocabulaire impactant et de hashtags spécifiques contribue à encourager le public, en particulier les jeunes, à s’engager dans la lutte contre le changement climatique.

## Technologies

- Python : `snscrape`, `pandas`, `nltk`, `spacy`, `matplotlib`

## Auteurs

- Patricia Augustyn
- Lise Brisset
- Laurine Sautreau
