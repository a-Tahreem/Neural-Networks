# Deep Learning: Comparaison entre Modèles Profonds et Peu Profonds

## Description
Ce projet explore l'impact du nombre de couches cachées sur les performances des réseaux de neurones en utilisant des **modèles peu profonds** et **modèles profonds**. L'objectif principal est de comparer ces deux approches à travers un jeu de données spécifique, tout en mettant en évidence leurs forces, leurs limites et les scénarios d'application optimaux.

---

## Sommaire du Notebook

1. **Introduction**
   - Contexte et objectifs.
   - Aperçu des réseaux de neurones peu profonds et profonds.
2. **Préparation des données**
   - Description, exploration, et nettoyage des données.
3. **Construction des modèles**
   - Mise en place des architectures avec différentes profondeurs (1 à 2 couches vs plus de 5 couches).
4. **Entraînement et évaluation**
   - Comparaison des performances selon des critères tels que la précision, la perte, et le temps d'entraînement.
5. **Analyse des résultats**
   - Discussion des scénarios d'utilisation optimaux pour chaque type de modèle.

---

## Technologies et Outils

- **Langage** : Python 3.8+
- **Bibliothèques** :
  - **Keras** : Construction et entraînement des modèles.
  - **TensorFlow** : Backend pour l'exécution des modèles.
  - **Matplotlib** : Visualisation des résultats.
  - **Pandas** : Manipulation et exploration des données.
  - **NumPy** : Calculs numériques.

---

## Résultats Clés

- Les **modèles profonds** montrent des performances supérieures pour les jeux de données complexes, mais nécessitent davantage de ressources et de temps d'entraînement.
- Les **modèles peu profonds** offrent des résultats rapides et efficaces pour les tâches moins complexes, avec un coût calculatoire réduit.

---

## Exécution

### Prérequis
1. Assurez-vous d'avoir installé Python 3.8 ou une version supérieure.
2. Installez les dépendances nécessaires :
   ```bash
   pip install pandas numpy scikit-learn tensorflow matplotlib 
3. Ouvrez un terminal et exécutez la commande suivante :
   ```bash
   jupyter notebook DL-NL.ipynb

---

## Objectifs du TP

- Comparer les performances des modèles peu profonds et profonds.
- Identifier les scénarios où les modèles profonds surpassent les modèles peu profonds.
- Évaluer les compromis entre complexité du modèle, temps dentraînement et précision.

-- 
## References

1. **Keras Documentation**: [Keras Official Website](https://keras.io/)
   - A powerful deep learning library built on top of TensorFlow. Provides high-level APIs for building and training neural networks.

2. **TensorFlow Tutorials**: [TensorFlow Official Tutorials](https://www.tensorflow.org/tutorials)
   - Comprehensive guides and examples for building machine learning models using TensorFlow.

3. **Deep Learning Book**: [Ian Goodfellow et al.](https://www.deeplearningbook.org/)
   - A widely recognized resource covering the fundamentals and advanced topics in deep learning.

4. **NumPy Documentation**: [NumPy Official Website](https://numpy.org/doc/)
   - Essential for numerical computations in Python, used heavily in deep learning projects.

5. **Pandas Documentation**: [Pandas Official Website](https://pandas.pydata.org/docs/)
   - A fast and flexible data manipulation library, ideal for data preprocessing.

6. **Matplotlib Documentation**: [Matplotlib Official Website](https://matplotlib.org/stable/contents.html)
   - A versatile library for creating static, interactive, and animated visualizations in Python.
