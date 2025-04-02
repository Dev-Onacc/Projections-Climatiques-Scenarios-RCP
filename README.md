# 🌍 Projections Climatiques - Scénarios RCP

Cette application Streamlit permet de simuler des **projections climatiques** à partir de données météorologiques locales, selon différents **scénarios RCP (Representative Concentration Pathways)** issus des rapports du GIEC (IPCC AR6).

---

## 📦 Fonctionnalités

- 📤 Importation de fichiers Excel (.xlsx) contenant des données météorologiques historiques
- 🌍 Sélection de la localité et plage temporelle
- 🌡️ Application des scénarios climatiques RCP (2.6, 4.5, 8.5)
- 📈 Visualisations interactives des projections de température et de précipitations
- 📊 Comparaison des scénarios à l’échelle mensuelle
- 💾 Export des données projetées au format Excel
- 📚 Références scientifiques intégrées

---

## 🧪 Scénarios climatiques implémentés

| Scénario | Évolution température | Évolution précipitation | Variabilité | Description |
|----------|-----------------------|--------------------------|-------------|-------------|
| RCP2.6   | +0.01 / an            | +0.005 / an              | 0.10        | Réchauffement limité à +1.5°C |
| RCP4.5   | +0.023 / an           | +0.008 / an              | 0.15        | Stabilisation modérée |
| RCP8.5   | +0.045 / an           | +0.015 / an              | 0.25        | Émissions non atténuées |

Les projections intègrent une **variabilité stochastique** pour simuler les fluctuations climatiques naturelles.

---

## 📂 Format de données attendu

Le fichier Excel importé doit contenir les colonnes suivantes :

| Colonne         | Description                          |
|-----------------|--------------------------------------|
| `localite`      | Nom de la localité                   |
| `date`          | Date de l'observation (YYYY-MM-DD)   |
| `temp-max`      | Température maximale quotidienne (°C)|
| `temp-moy`      | Température moyenne quotidienne (°C) |
| `temp-min`      | Température minimale quotidienne (°C)|
| `precipitation` | Précipitations journalières (mm)     |

---

## 🚀 Lancer l’application

1. **Installer les dépendances :**

```bash
pip install -r requirements.txt
```

2. **Exécuter l'application :**

```bash
streamlit run app.py
```

---

## 🧠 Références scientifiques

- **GIEC (IPCC AR6)** – Sixth Assessment Report: [https://www.ipcc.ch/assessment-report/ar6/](https://www.ipcc.ch/assessment-report/ar6/)
- Modèle de variabilité climatique basé sur des méthodes stochastiques
- Coefficients d’ajustement inspirés des projections régionales IPCC

---

## ✍️ Auteur

Développé par **POUM BIMBAR Paul Ghislain/ ONACC**  
🔬 Spécialiste en modélisation climatique et science des données
poum.bimbar@onacc.cm

---

## 📃 Licence

Ce projet est proposé à des fins éducatives et scientifiques.  
Pour un usage professionnel ou institutionnel, merci de contacter l’auteur.