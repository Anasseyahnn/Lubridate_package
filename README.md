# 📅 Manipulation des dates en R avec lubridate

![Version](https://img.shields.io/badge/Version-1.0-blue)
![R Version](https://img.shields.io/badge/R-%3E%3D%204.1.0-lightgrey)
![License](https://img.shields.io/badge/License-MIT-green)

> Un guide complet et pratique pour maîtriser la manipulation des dates en R à travers un projet d'analyse de données de vente.

<p align="center">
  <img src="https://raw.githubusercontent.com/tidyverse/lubridate/master/man/figures/logo.png" alt="lubridate logo" width="200"/>
</p>

## 📋 Présentation

Ce projet est un guide complet pour la manipulation des dates en R avec le package `lubridate`, illustré par une analyse approfondie de données de vente. Il est conçu comme un support pédagogique pour les étudiants en science des données qui rencontrent des difficultés avec la gestion des dates dans leurs analyses.

## 🎯 Objectifs

- Démystifier la manipulation des dates en R
- Fournir des exemples concrets et applicables
- Présenter les bonnes pratiques à travers un projet de bout en bout
- Offrir une ressource pratique pour les analystes de données

## 📊 Contenu du projet

### 1. Fondamentaux de lubridate
- Installation et chargement
- Création de dates avec différents formats
- Extraction et modification des composants d'une date
- Arithmétique des dates

### 2. Projet d'analyse de données de vente
- Génération d'un jeu de données réaliste avec patterns saisonniers
- Exploration multidimensionnelle des tendances temporelles
- Analyse comparative par période, magasin et jour de la semaine
- Identification des jours exceptionnels et intervalles entre pics de vente
- Prévision basée sur les patterns historiques

### 3. Techniques avancées
- Périodes glissantes (rolling periods)
- Calcul d'intervalles entre événements
- Analyse par saison commerciale personnalisée
- Formatage des dates pour affichage
- Gestion des fuseaux horaires et des valeurs manquantes

## 🛠️ Technologies utilisées

- **R** - Langage de programmation principal
- **R Quarto** - Pour la documentation et le blog
- **lubridate** - Package principal pour la manipulation des dates
- **tidyverse** (dplyr, ggplot2) - Pour la manipulation et visualisation des données
- **scales** - Pour le formatage des échelles dans les visualisations

## 🚀 Comment utiliser ce projet

### Prérequis

```r
# Installation des packages nécessaires
install.packages(c("lubridate", "dplyr", "ggplot2", "tidyr", "scales"))
```

### Structure du projet

```
lubridate-tutorial/
├── README.md               # Ce fichier
├── lubridate-tutorial.qmd  # Document Quarto principal
├── _site/                  # Site généré par Quarto
│   └── index.html          # Page principale du blog
└── data/                   # Données (générées dans le script)
```

### Exécution du projet

1. Clonez ce dépôt:
   ```bash
   git clone https://github.com/votre-nom/manipulation-dates-r.git
   ```

2. Ouvrez le fichier `lubridate-tutorial.qmd` dans RStudio ou votre éditeur préféré

3. Exécutez le document Quarto:
   ```bash
   quarto render lubridate-tutorial.qmd
   ```

4. Visualisez le résultat dans votre navigateur:
   ```bash
   quarto preview
   ```

## 📈 Aperçu des visualisations

![unnamed-chunk-11-1](https://github.com/user-attachments/assets/2d7e76f7-a1f0-4498-9478-972e8edd5921)

![unnamed-chunk-10-1](https://github.com/user-attachments/assets/08dec6bb-f5b6-410b-b43c-ac3d82ffaae9)

![unnamed-chunk-17-1](https://github.com/user-attachments/assets/d5f77303-62c1-44a5-9245-e5c1827d1284)

![unnamed-chunk-13-1](https://github.com/user-attachments/assets/e29c1573-6177-41b0-9d1e-594a58ce5997)


## 🎓 Public cible

- Étudiants en science des données
- Analystes et data scientists
- Professionnels travaillant avec des données temporelles
- Enseignants en programmation R

## 📚 Ressources complémentaires

- [Documentation officielle de lubridate](https://lubridate.tidyverse.org/)
- [R for Data Science](https://r4ds.hadley.nz/) - Chapitre sur les dates et heures
- [Quarto Guide](https://quarto.org/docs/guide/) - Pour personnaliser la présentation

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à:
- Signaler des problèmes ou bugs
- Proposer des améliorations
- Ajouter de nouveaux exemples ou cas d'usage
- Améliorer la documentation

## 📝 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 👤 Auteur

- Anassé Yahanan - [Mon Portfolio](https://anasseyahnn.github.io/Anasseyahnn-wbs/) - [LinkedIn](https://www.linkedin.com/in/anasse-yahanan-bouagba-3b39aa242/)

---

<p align="center">
  <a href="https://github.com/votre-nom/manipulation-dates-r/stargazers">
    <img src="https://img.shields.io/github/stars/votre-nom/manipulation-dates-r?style=social" alt="Stars"/>
  </a>
  <a href="https://github.com/votre-nom/manipulation-dates-r/network/members">
    <img src="https://img.shields.io/github/forks/votre-nom/manipulation-dates-r?style=social" alt="Forks"/>
  </a>
</p>

<p align="center">
  Développé avec ❤️ pour la communauté R
</p>
