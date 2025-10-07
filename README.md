# Analyse des ventes de vin – Projet BottleNeck

Ce projet a été réalisé dans le cadre du **Module Expert Data Analyst** sur **OpenClassrooms**.  
L’objectif était de détecter les incohérences entre plusieurs sources de données et d’analyser les ventes de vin pour l’entreprise fictive **BottleNeck**, en utilisant exclusivement **Python** sur **Google Colab**.

---

## 🎯 Objectifs du projet
- Détecter les incohérences entre les fichiers ERP, Web et Liaison  
- Fusionner les trois fichiers en un seul jeu de données cohérent  
- Vérifier la cohérence des ventes et calculer le **chiffre d’affaires (CA)**  
- Étudier la **distribution des prix** et identifier les **outliers**  

---

## 🧰 Outils et bibliothèques utilisés
- **Python**  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scipy.stats (zscore)  
- **Google Colab** pour l’exécution du notebook  
- **Excel / Google Sheets** pour la préparation initiale des fichiers  

---

## 🧹 Étapes principales de l’analyse
1. **Importation et préparation des données**
   - Chargement des trois fichiers : `erp.xlsx`, `web.xlsx`, `liaison.xlsx`  
   - Exploration initiale et vérification des colonnes  
2. **Nettoyage des données**
   - Gestion des valeurs manquantes et doublons  
   - Normalisation des noms de colonnes et des formats  
   - Harmonisation des clés pour la fusion  
3. **Fusion des jeux de données**
   - Création d’un dataset complet à partir des trois sources  
   - Vérification des jointures et des correspondances  
4. **Calcul et vérification du chiffre d’affaires**
   - Création d’une colonne CA = `prix * quantités`  
   - Analyse de cohérence des montants  
5. **Analyse exploratoire**
   - Étude de la distribution des prix du vin  
   - Détection des valeurs aberrantes via la méthode du Z-Score  
   - Visualisation des tendances à l’aide de **Seaborn** et **Matplotlib**

---

## 📊 Résultats clés
- Données consolidées avec succès à partir des trois sources ERP, Web et Liaison  
- Calcul d’un chiffre d’affaires global fiable après correction des incohérences  
- Identification de plusieurs **outliers de prix** suggérant des erreurs de saisie ou des valeurs extrêmes  
- Visualisations claires de la distribution des prix et du CA  

---

## 👩‍💻 Auteur
**Sylvia Chevalier** – Data Analyst  
- Formation *Module Expert Data Analyst – OpenClassrooms*  
- Projet réalisé exclusivement sur **Python (Google Colab)**  
- Intérêt pour l’analyse de données appliquée aux secteurs **commerciaux et de la santé**

[Mon profil LinkedIn](https://[www.linkedin.com/in/...](https://www.linkedin.com/in/sylvia-chevalier-data-analyst/#:~:text=www.linkedin.com/in/sylvia%2Dchevalier%2Ddata%2Danalyst))  
[Voir le Notebook sur Google Colab](https://colab.research.google.com/drive/1fYnCHv46vDj6XlKcSv3p2uLz95tnJPz4?usp=sharing)  

---

## 🙏 Remerciements
Merci à mon **mentor OpenClassrooms** pour son accompagnement et ses conseils tout au long du projet.

