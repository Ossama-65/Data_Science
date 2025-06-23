# Data Science

## Contexte et Objectifs

Ce projet Data Science vise à développer et comparer plusieurs modèles prédictifs pour une tâche spécifique (à préciser selon le domaine de données). Il inclut la préparation des données, l'entraînement des modèles, l'évaluation des performances et la génération de prédictions finales.

## Structure du dépôt

```
├── modele_datascience_2.ipynb      # Notebook Jupyter : première version du modèle
├── Model_datascience_4.ipynb       # Notebook Jupyter : version améliorée du modèle
├── Model1_version_final 1.ipynb    # Notebook Jupyter : version finale du modèle 1
├── predictions_model1.csv          # Fichier CSV des prédictions issues du modèle final
```

## Prérequis

* Python 3.7 ou supérieur
* Jupyter Notebook ou JupyterLab
* Bibliothèques Python :

  * pandas
  * numpy
  * scikit-learn
  * matplotlib
  * seaborn
  * joblib (pour la sérialisation des modèles)

## Installation

1. Cloner le dépôt :

   ```bash
   git clone https://github.com/Ossama-65/Data_Science.git
   cd Data_Science
   ```

2. (Optionnel) Créer et activer un environnement virtuel :

   ```bash
   python -m venv venv
   source venv/bin/activate  # sur Linux/macOS
   venv\\Scripts\\activate   # sur Windows
   ```

3. Installer les dépendances :

   ```bash
   pip install -r requirements.txt
   ```

> **Remarque** : Si le fichier `requirements.txt` n'existe pas, installez manuellement les packages listés dans la section **Prérequis**.

## Usage

1. **Exploration et préparation des données** :

   * Charger et nettoyer les données directement dans les notebooks.
   * Effectuer l’analyse exploratoire (visualisations, statistiques descriptives).

2. **Entraînement des modèles** :

   * Exécuter les notebooks dans l’ordre :

     1. `modele_datascience_2.ipynb` pour la version initiale.
     2. `Model_datascience_4.ipynb` pour la version améliorée.
     3. `Model1_version_final 1.ipynb` pour la version finale.

3. **Évaluation** :

   * Consulter les métriques (accuracy, precision, recall, F1-score) affichées dans chaque notebook.

4. **Prédictions** :

   * Les résultats du modèle final sont dans `predictions_model1.csv`.

## Résultats

* Comparaison des performances des différents modèles.
* Visualisations des courbes ROC et matrices de confusion intégrées dans les notebooks.
* Fichier `predictions_model1.csv` prêt à être utilisé pour la phase de déploiement ou de soumission.

## Contribution

Les contributions sont les bienvenues :

* Ajout de nouvelles fonctionnalités ou modèles.
* Optimisation des pipelines de nettoyage et d’entraînement.
* Documentation et tests unitaires.

## Auteur

* Zerguit Manel
* Louridi Ossama

## Licence

Ce projet est sous licence MIT. Consultez le fichier `LICENSE` pour plus de détails.
