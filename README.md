# Méthode 2 : Déploiement automatique d'un CV avec GitHub Actions

## Présentation du projet

Ce projet est un **CV en ligne** développé à l’aide du générateur de sites statiques **Hugo**.  
Il permet de présenter mon profil professionnel, mon parcours académique, mes expériences, mes compétences et mes projets sous la forme d’un site web moderne et responsive.

Le site est automatiquement généré et mis à jour grâce à **GitHub Actions**, puis publié via **GitHub Pages**.

## Objectifs du projet

- Disposer d’un CV accessible en ligne
- Présenter mon profil de manière professionnelle
- Faciliter les mises à jour du contenu
- Utiliser une solution moderne et automatisée

## Prérequis
- Un compte GitHub
- VSCode installé sur votre ordinateur
- Git installé sur votre système
- Hugo installé ([Guide d'installation Hugo](https://gohugo.io/installation/))

## Structure du projet
```
   GITHUB/
   ├── docs/
   │   ├── pictures/
   │   └── Guide.md
   ├── layouts/
   │   └── index.html
   ├── static/
   ├── themes/
   ├── hugo.toml
   ├── config.yaml
   └── README.md
```

### Description des éléments principaux

- **layouts/** : fichiers HTML du thème (structure des pages)
- **static/** : fichiers statiques (images, CSS, icônes)
- **themes/** : thème Hugo utilisé pour le CV
- **config.toml** : configuration générale du site
- **docs/** : documentation et ressources complémentaires
- **README.md** : description du projet

## Accès au site

https://votre-nom.github.io

## Remarque

Le contenu du CV peut être personnalisé en modifiant les fichiers Hugo (contenu et layouts) selon les besoins.
