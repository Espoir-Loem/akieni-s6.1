# Yidi — Studio de Product Design

Site vitrine 3 pages pour Yidi, un studio de product design (UI/UX & stratégie)
basé à Brazzaville. Projet 6.1 — HTML5 + CSS3 purs, sans framework.

## Pages

- **Accueil** (`index.html`) : Hero, statistiques, méthodologie, services, portfolio, témoignages, partenaires
- **Services** (`services.html`) : Prestations détaillées (UI Design, UX Research, Design System, Stratégie Produit)
- **Contact** (`contact.html`) : Formulaire de contact + coordonnées

## Design system

- **Palette** : `--ink` (#0e1512), `--paper` (#f6f3ec), `--signal` (#c9ff3d), `--canopy` (#1f3d2b)
- **Typographies** : Fraunces (titres), Inter (corps), JetBrains Mono (éléments techniques)
- **Signature visuelle** : Coins crop-mark (`frame`), motifs pointillés, étiquettes numérotées

## Lancer en local

Aucune dépendance. Ouvrir `index.html` dans un navigateur ou :

```bash
python3 -m http.server 8000
```

## Déploiement GitHub Pages

1. Pusher le dépôt sur GitHub
2. Settings → Pages → Deploy from branch `main`, dossier `/ (root)`

## Structure

```
├── index.html
├── services.html
├── contact.html
├── assets/css/style.css
└── README.md
```
