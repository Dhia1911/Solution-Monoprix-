# 🛒 Solution-Monoprix

Ce dépôt réunit deux volets complémentaires pour améliorer la performance de Monoprix :

- 🔍 **Des algorithmes de Machine Learning**
- 📊 **Des tableaux de bord Power BI**

---

## 🎯 Objectifs du projet (Business & Data Science)

Ce projet répond à une feuille de route stratégique axée sur l'optimisation des performances :

### 🔧 1. Optimiser la gestion financière
- Accélérer les paiements fournisseurs
  - Suivre les paiements
  - Détecter les retards avec l’IA
  - Automatiser les relances
- Renforcer le contrôle financier
  - Détecter les erreurs
  - Identifier les fraudes
  - Réduire les coûts et augmenter les revenus
- Suivre les KPI via Power BI

### 📈 2. Optimiser le positionnement sur le marché
- Analyse des prix concurrents
- Analyse des promotions
- Positionnement produit
- Analyse des avis clients

### 🏪 3. Accroître la rentabilité des magasins
- Identifier les "produits magiques"
- Améliorer l'efficacité opérationnelle

---

## 📁 Contenu du dépôt

### 🔬 Notebooks Jupyter (Machine Learning)

| Fichier                              | Objectif couvert                                   |
|--------------------------------------|----------------------------------------------------|
| `clustering_litiges_final.ipynb`     | Segmentation des litiges fournisseurs              |
| `Erreur.ipynb`                       | Détection des erreurs comptables                   |
| `obj_descriptif(detect erreur).ipynb`| Analyse descriptive des anomalies                  |
| `Retard-objectif.ipynb`             | Prédiction des retards fournisseurs                |
| `Revenue-obj.ipynb`                 | Prédiction des revenus futurs                      |

### 📊 Dashboards Power BI

| Fichier ou Rapport                  | Objectif couvert                                   |
|-------------------------------------|----------------------------------------------------|
| `Dashboard_Finance.pbix`           | Suivi des indicateurs financiers (DPO, DSO, etc.) |
| `Dashboard_Produits.pbix`          | Analyse produit, promotions, "produits magiques"  |
| `Dashboard_Concurrence.pbix`       | Comparaison dynamique des prix et du marché       |
| `Dashboard_Opérations.pbix`        | KPI magasins, efficacité opérationnelle            |

---

## 🧠 Technologies utilisées

- **Python**, **Scikit-Learn**, **Pandas**, **Jupyter**
- **Power BI**
- Git / GitHub

---

## 🛠️ Lancer le projet ML en local

```bash
git clone https://github.com/Dhia1911/Solution-Monoprix-.git
cd Solution-Monoprix-
jupyter notebook
