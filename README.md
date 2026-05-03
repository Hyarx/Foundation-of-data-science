# Foundation-of-data-science

Master 1 Data Science Engineering, Université de Liège (ULiège).

## Notebooks

**`hw1` — Exploratory Data Analysis of Pulse Oximetry Data**
Chargement, nettoyage et exploration du dataset [OpenOximetry](https://physionet.org/content/openox-repo/1.0.1) (données patients, rencontres cliniques, mesures de gaz sanguins). Fusion des tables, détection d'outliers par IQR, statistiques descriptives et visualisations des distributions démographiques et physiologiques.

**`hw2` — Inference of Oxygen Saturation from Photoplethysmography**
Construction d'un modèle probabiliste reliant la saturation en oxygène (SpO₂) aux signaux PPG via la loi de Beer-Lambert. Traitement du signal (extraction des cycles cardiaques, composantes AC/DC), calcul du ratio de pulsativité et estimation des paramètres par maximum de vraisemblance.

**`hw3` — Bayesian Inference of Oxygen Saturation from Photoplethysmography**
Extension bayésienne du HW2 : choix et discussion des distributions a priori, échantillonnage de la distribution a posteriori par MCMC (`emcee`), analyse de convergence des chaînes de Markov et vérifications prédictives a posteriori.

**`hw4` — Heart Failure Prediction with Survival Analysis**
Analyse exploratoire d'un dataset clinique d'insuffisance cardiaque (299 patients), puis modélisation par un modèle de Cox à risque proportionnel. Inférence bayésienne des paramètres, comparaison de modèles (hypertension vs. tabagisme), courbes de survie prédictives et critique du modèle.
