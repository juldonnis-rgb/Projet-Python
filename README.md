📊 Simulation Data Analyst : Exploration du Marché des Animés
Ce projet simule une mission de Data Analyst consistant à explorer, nettoyer et visualiser un jeu de données contenant des informations détaillées sur des animés populaires (notes, studios, épisodes, statuts).

🎯 Objectifs du Projet
Data Cleaning : Chargement et vérification de l'intégrité des données via Pandas.

Analyse Statistique : Calcul des tendances (moyennes, records, répartition des studios).

Visualisation de Données : Création de graphiques pour identifier la distribution des notes et l'état d'avancement des séries.

🛠️ Stack Technique
Langage : Python 3.x

Bibliothèques :

Pandas (Manipulation et analyse de données)

Matplotlib (Visualisation graphique)

📋 Structure du Dataset (animes.csv)
Le fichier de données contient 59 entrées avec les colonnes suivantes :

Anime : Nom de la série.

Note_Globale : Score moyen sur 10.

Studio : Studio d'animation responsable de la production.

Nb_Episodes : Nombre total d'épisodes.

Status : État de la série (Fini, En cours, En pause).

Meilleur_Ep_Titre : Titre de l'épisode le mieux noté par la communauté.

🚀 Installation et Utilisation
1. Cloner le dépôt
Bash
git clone https://github.com/ton-pseudo/nom-du-repo.git
cd nom-du-repo
2. Installer les dépendances
Assurez-vous d'avoir Python installé, puis installez les bibliothèques nécessaires :

Bash
pip install pandas matplotlib
3. Exécuter l'analyse
Pour lancer le script et générer les rapports dans le terminal ainsi que les graphiques :

Bash
# Sur Windows (Git Bash)
winpty python projet_python.py

# Sur Mac/Linux
python3 projet_python.py
📈 Aperçu des Résultats
Analyse Descriptive
Le script génère automatiquement les insights suivants :

Top 10 des animés les mieux notés (ex: Frieren, Fullmetal Alchemist: Brotherhood).

Statistiques générales : Moyenne globale des notes et volume moyen d'épisodes par série.

Domination des Studios : Classement des studios les plus prolifiques du dataset.

Visualisations
Deux graphiques majeurs sont générés pour l'aide à la décision :

Histogramme des notes : Pour comprendre si la majorité des animés se situent dans une tranche de qualité spécifique.

Bar Chart des Statuts : Pour visualiser la proportion de séries terminées par rapport aux séries en cours.

Note d'analyse : La ligne rouge sur l'histogramme représente la moyenne globale, permettant d'identifier immédiatement les "Outliers" (les animés exceptionnels).

👤 Auteur
Juldonnis Razafimanazato Apprenti Développeur Web & Data Enthusiast Mon Portfolio
