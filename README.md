# Yidi — Site vitrine (Projet 6.1)

Site vitrine 3 pages pour **Yidi**, studio de product design basé à Brazzaville.
Projet réalisé dans le cadre du programme **Akieni Academy — Phase 2** (HTML, CSS & Git).

**Durée :** 6–7 heures

---

## Pages

| Page | Fichier | Contenu |
|------|---------|---------|
| Accueil | `index.html` | Hero, présentation, services, portfolio, témoignages, partenaires |
| Services | `services/index.html` | UI Design, UX Research, Stratégie Produit — 3 prestations détaillées |
| Contact | `contact/index.html` | Formulaire de contact, email, adresse, réseaux |

## Fonctionnalités

- Logo et identité visuelle cohérente
- Navigation fonctionnelle avec `aria-current`
- Hero section avec image de fond
- Cards pour les services et réalisations
- Formulaire de contact fonctionnel
- Footer complet (liens, copyright, réseaux)
- Design responsive (2 breakpoints)

## Stack technique

| Technologie | Usage |
|-------------|-------|
| HTML5 | Structure sémantique (header, main, section, footer, nav) |
| CSS3 | Design system, Flexbox, Grid, variables CSS |
| Google Fonts | Fraunces, Inter, JetBrains Mono |
| Aucune dépendance | Pas de framework ni de bibliothèque externe |

## Design system

- **Palette :** `--ink` (#0e1512), `--paper` (#ffffff), `--signal` (#c9ff3d), `--canopy` (#1f3d2b)
- **Typographie :** Fraunces (titres), Inter (corps), JetBrains Mono (monospace)
- **Signature visuelle :** Coins crop-mark (`.frame`), motifs pointillés, étiquettes numérotées

## Structure du projet

```
├── index.html
├── services/index.html
├── contact/index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   └── images/
│       ├── home/
│       └── services/
└── README.md
```

## Lancer en local

Aucune dépendance. Ouvrir `index.html` dans un navigateur.

## Déploiement (GitHub Pages)

1. Pousser le dépôt sur GitHub
2. **Settings → Pages** : Deploy from branch `main`, dossier `/ (root)`
3. Le site est accessible à l'URL fournie par GitHub Pages

## Critères de validation

- [x] 3 pages HTML valides
- [x] Navigation fonctionnelle entre les pages
- [x] Design cohérent (couleurs, typographie, espacement)
- [x] Responsive mobile + desktop
- [x] 10+ commits Git
- [x] README documenté
- [x] Déploiement GitHub Pages actif
