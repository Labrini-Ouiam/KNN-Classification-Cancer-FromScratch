# Classification - KNN (From Scratch)

Ce projet implémente un algorithme de **K plus proches voisins (KNN)** depuis zéro (sans bibliothèque de machine learning) pour effectuer une **classification binaire** liée à la détection du cancer.

## 📁 Dépôt GitHub

🔗 [KNN-Classification-Cancer-FromScratch](https://github.com/Labrini-Ouiam/KNN-Classification-Cancer-FromScratch.git)

---

## 🧪 Objectifs du TP

1. **Déterminer le nombre optimal de voisins (K)** à partir du dataset fourni.
2. **Implémenter l'algorithme KNN from scratch** pour prédire la **présence ou non d’un cancer**.
3. **Générer un dataset synthétique** avec différents niveaux de **bruit**, puis :
   - Tester plusieurs valeurs de `K`
   - Sélectionner le `K` optimal
   - Interpréter les résultats

---

## 🧠 Méthodologie

- Chargement et exploration du dataset
- Séparation des données en train/test
- Calcul des distances (euclidiennes)
- Classification par majorité des K plus proches voisins
- Évaluation du modèle avec la précision (`accuracy`)
- Génération de jeux de données synthétiques bruités
- Analyse de l’impact du bruit sur la performance et le choix de K

---

## 📈 Résultats attendus

- Courbes de performance (accuracy vs. K)
- Observations sur la sensibilité au bruit
- Meilleur compromis entre biais et variance

---

## 📂 Fichiers du Projet

- `KNN_Cancer_FromScratch.ipynb` : Implémentation principale du modèle KNN
- `cancer_dataset.csv` : Fichier original utilisé pour la classification
- `synthetic_data_generator.ipynb` : Génération de jeux de données bruités et analyse

---

## 🛠️ Technologies utilisées

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

> ⚠️ Aucun usage de `scikit-learn` ou autre bibliothèque ML pour le cœur de l’algorithme.

---

## 👩‍💻 Auteur

**Labrini Ouiam**  

---

> Pour toute remarque, merci d’ouvrir une issue ou soumettre un pull request.
