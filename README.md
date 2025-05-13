# 🛒 Défi Carrefour IA – Prédiction de réachat client

Ce projet a été réalisé dans le cadre d’un défi d’intelligence artificielle proposé par Carrefour et l'université de Bordeaux. L’objectif est de prédire les produits qu’un client est susceptible de racheter à partir de son historique d’achat.

## 🎯 Objectif
Développer un moteur de prédiction capable de recommander les **10 produits les plus susceptibles d’être rachetés** par 20 000 clients, en se basant sur :
- L’historique des transactions
- Les informations produits
- Les métadonnées clients

## 🧠 Approche
- Nettoyage et structuration des données
- Feature engineering (fréquence d’achat, récence, score TF-IDF, etc.)
- Entraînement de modèles de machine learning (baseline, modèles avancés)
- Évaluation via la métrique **Hit Rate @10**
- Génération du top 10 des produits prédits pour chaque client

## 📁 Fichier fourni
- `final.ipynb` : notebook complet contenant le traitement, la modélisation et les prédictions

## 📊 Résultats
- Score de validation obtenu (Hit Rate @10) : **36%**
- Méthodes testées : baseline par fréquence, modèles personnalisés, apprentissage supervisé

## 📌 Remarques
Le notebook peut être exécuté dans un environnement Python standard avec les bibliothèques :
- pandas, numpy, sklearn, matplotlib, seaborn, xgboost, lgbm.

## 👨‍💻 Auteur
Projet réalisé par **Kamagate Youssouf**, étudiant en data science.

📧 kamagatey25@gmail.com  
📞 +225 0779837708
